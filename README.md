An app that mimics Eventbrite 
You can also get to my app on Heroku by following the link : https://eventbrite-v2.herokuapp.com/

Instructions :

1)Make a git clone: https://github.com/Frozenmouth/The_Gossip_Project 

2) Install gems: `bundle install`

In your terminal, please enter the following commands : 

3) `rake db:drop`

4) `rake db:create`

5) `rake db:migrate`

6) `rake db:seed`

And now, launch your local server with the following command :

7) `rails s`

You can now use the application. Enjoy! :)

⚠️ A l'attention des correcteurs qui vont checker mon projet demain matin ⚠️
La version de Ruby que j'utilise (2.5.3) n'est pas la meme que celle utilisee par les moussaillons qui effectuent le parcours. Il se peut que la difference de version cree des incomptabilites et empeche la bonne execution de l'appli Rails. Mais pas de panique, voici une solution (un peu barbare, certes) pour y remedier :

Modifiez la version de Ruby dans le Gemfile en fonction de celle que vous utilisez sur votre PC
Supprimez le fichier Gemfile.lock
Faites un bundle install dans le terminal : Normalement tout fonctionne !