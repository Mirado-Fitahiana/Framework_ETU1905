# Framework_ETU1905
 
-Sprint 1:
redirection vers FrontServlet   

-Sprint 2:
Creation classe mapping 
    String className;
    String method;
Front Servlet :
    HashMap<String, Mapping> mappingUrls;  
    
-Sprint 3:
    Remplissage du  HashMap<String, Mapping> mappingUrls dans la fonction init
    Liste fonction annote
    Liste classe dans le package classe annote
    
-Sprint 4:
<<<<<<< Updated upstream
    Séparer dans framework les classes telles que : Frontservlet, Utils, Url et Mapping puis dans test-framework les classes de test, web.xml, fichiers jsp
=======
    Séparer dans framework les classes telles que : Frontservlet, Utils, Url et Mapping puis dans test-framework les classes de test, web.xml, fichiers jsp

-Sprint 5:  
    -Comparer l'url obtenu avec la liste annotations dans Hashmap.getKey, si il ya correspondance voir si la méthode retourne modelView et puis renvoyer dans sa page qui correspond à l'attribut vue dans ModelView

-Sprint 6:
    -Ajout d' un attribut data de type HashMap et fonction addItem pour ajouter des valeurs dans data
    -Récupérer les valeurs des fields des classes et puis ajouter dans data et renvoyer dans le modelView correspondant et afficher les valeurs
>>>>>>> Stashed changes
