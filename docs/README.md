






# 👋  Welcome to Qyrus Documentation!!

<script  type="text/javascript">
    function initKeycloak() {
        console.log("here")
        const keycloak = new Keycloak({
            url: 'http://keycloak:8180/auth',
            realm: 'SpringBoot',
            clientId: 'test',
           
        });
        keycloak.init({onLoad: 'login-required'}).then(function(authenticated) {
          console.log(authenticated);
             alert(authenticated ? 'authenticated' : 'not authenticated');
        }).catch(function() {
            alert('failed to initialize');
        });
    } 
    initKeycloak(); 
  </script>   