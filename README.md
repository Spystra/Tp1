## Partie 1: 


4. 
   ```bash
   git config --global --list
   ```

5. 
   ```bash
   git config --global user.email "nouvelle.adresse@example.com"
   ```

---

## Partie 2: 

6. 
   ```bash
   touch README.md
   git add README.md
   git commit -m "Ajout du fichier README.md"
   git push origin main
   ```

7. 
   ```bash
   git remote add origin https://github.com/username/nom-du-depot.git
   git remote -v
   ```

---

## Partie 3: 

3. 
   ```bash
   git checkout -- nom_du_fichier
   ```

4. 
   ```bash
   git status
   ```

---

## Partie 4:

4. 
   ```bash
   git remote add origin URL_DU_DEPOT
   git fetch origin
   git branch -r
   ```

5. 
   ```bash
   git branch -d nom_de_la_branche
   ```

---

## Partie 5: 


8. 
   ```bash
   git rebase --abort
   ```

9. 
   ```bash
   git log source_branch..target_branch
   ```

---

## Partie 6:

8. 
   ```bash
   git flow config list
   ```

9. 
   ```bash
   git flow hotfix delete nom_du_correctif
   ```

---
