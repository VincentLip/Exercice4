EXERCICE n°4 :   
Effectuer les différents jeux présent sur ce site :   
https://learngitbranching.js.org/?locale=fr_FR   


#Séquence d'introduction   

Question 1   
git commit   
git commit   

Question 2   
git branch bugFix   
git checkout bugFix   

Question 3   
git branch bugFix       
git checkout bugFix   
git commit -m C2   
git checkout main   
git commit -m C3   
git merge bugFix   

Question 4   
git branch bugFix      
git checkout bugFix   
git commit -m C2   
git checkout main   
git commit -m C3   
git checkout bugFix   
git rebase bugFix   

#Montée en puissance   

Question 1   
git checkout C4   

Question 2   
git checkout bugFix^   

Question 3   
git checkout HEAD^   
git branch -f main C6   
git branch -f bugFix C0   

Question 4   
git reset HEAD^   
git checkout pushed   
git revert pushed   

#Déplacer le travail   

Question 1   
git cherry-pick C3 C4   
git cherry-pick C7   

Question 2  
git rebase -i HEAD^^^^   

#Un assortiment   

Question 1   
git branch -f bugFix C1   
git checkout main   
git cherry-pick C4   

Question 2   
git rebase -i caption~2   
git commit --amend   
git rebase -i caption~2   
git branch -f main caption   

Question 3   









