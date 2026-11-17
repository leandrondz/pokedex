# pokédex

D'après la liste de Pokémon il y a 1025  
car "pokedex_id": 1025,  
  
Le nom en franvais danss chaque objet est ranger comme cela   
ex "fr": "Pêchaminus"  
   "fr": "Nom de Pokémon"  

  Le premier ellement n'est pas un vrai Pokémon car   lorsqu'on lis la catégorie c'est un pokemon
   "pokedex_id": 0,  
        "generation": 1,  
        "category": "Pokémon Bug",  
        "name": {  
            "fr": "MissingNo.",  
            "en": "MissingNo.",  
            "jp": "キャタピー"  
   



        
lors qu'un Pokémon n'existe pas le code renvoyer est le suivant   
{  
    "status": 404,  
    "message": "Impossible de trouver le Pokémon dans la base de données."  
}  
