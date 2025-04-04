# algo-Ia
pour la création d'une ia dans le cadre du cours d'algorithmie 2025

step 1 : ajouter les membre et les acces X

step 2 : déposer une base Unity fonctionnelle pour la création de terrain X

step 3 : creer un personnage mouvable "pablo ia"

step 3.1 : creer une sortie de fin de game 

step 4 : creer une ia et coonfig les condition 

step 5 : donner les commande a une ia X

step 6 : creer les contrainte des object X que sa fait des dégat et autre

step 7 : faire un meilleur affichage de fond ,point de vie, musique , afficher se que il comprend (une petite fenetre"pablo a décoouvert le piege X " ) 

step 8 : faire un mod "creation de map " pour faire des map custom 



step 4 : condition pour l'ia  : 
par défaut il sait tout se qui lui donne du score 
par défaut il ne connais pas se qui fait perdre du score (hormis le timer )

donner le bool connais le daner ou connais pas le danger 
donner une sorte de liste d'étape de mouvemnt a éxecuter  qui doit enregister si il réussi une ésquive 


si il connais pas le danger : ne le prend pas en compte 

  si il connais le danger : 
    essaie d'esquiver : 
        si il ne sait pas comment faire il essaie avec avec un mouvement simple 
        si il échoue essaie une autre manière d'ésquiver 
        si il réussi enregister comment il a fait et pourra le refaire dans la liste d'étape 
        
plus le temp passe plus il perd du score 
plus il perd des vie plus il perd du score 
plus il gagne des piesse plus il recupere du score 
plus il gagne des vie plus il récupere du score 

quand il atteint la sortie il gagne une grosse quantité de point de score pour lui dire "ca c'est important que tu l'atteint "

si il atteint la sortie la parti se stop et on regard les score. 

une fois tout ca fait il passe au niveau 2 et on voit en combien de temps il le fait cette fois (normalement il devrais avoir un meilleur score car il garde en mémoire ses consigne apris )

il doit apprendre que le mieux est de perdre un peux plus de temps mais de récuperer toute les piesse de la carte car il réussira avec un meilleur score 
