






# 👋  Welcome to Qyrus Documentation!!


<script type="text/javascript">
   
     function initKeycloak() 
    {
        console.log("here")
        const keycloak = new Keycloak(keycloakAuth);
        keycloak.init({onLoad: 'login-required'}).then(function(authenticated) {
        console.log(authenticated);
            alert(authenticated ? 'authenticated' : 'not authenticated');
        }).catch(function() {
            alert('failed to initialize');
        });
    } 
    initKeycloak(); 
  </script>   