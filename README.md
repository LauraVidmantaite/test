
#Mano pirmoji GIT repozitorija

si repozitorija skirta tam, kad ismokti naudotis git projektu versijavimo kontroles komandines eilutes sasaja (GIT CLI). Tam jums reikes parsisiusti ir isirasyti: https://git-scm.com/downloads

## Repozitorijos parsiuntimas
1. Atsidarykite GIT CLI (Git bash)
2. Naudodami komanda cd pakeiskite savo darbine kategorija i ta, kurioje norite parsisiusti repozitorija
3. Parsisiuskite repozitorija
4. Pakeiskite darbine kategorija i parsiustos repozitorijos kategorija cd <repozitroijos-pavadinimas>git ad
 Parsisiunte ir isirase GIT CLI, parsisiuskite repozitorija esamame kataloge 
git clone https://github.com/laa-vii/test
## Pagrindinės komandos
    git add - failu paruosimas patvirtinimui
    git add <failo-pavadinimas> -> prideda faila nurodytu pavadinimu
    git add . -> prideda pakitusius failus

git diff - skirtumuas tarp dvieju failu, ar dvieju to paties failo versiju
    git diff <failo-pavadinimas> -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o

 git status - parodo pakitusiu failu busena

 git branch -> komanda, kuria naudojama operacijoms su sakomis
    git branch -a -> parodo visas parsiustas sakas ir siuo metu aktyvia saka

git commit -> komanda, skirta uztvirtinit projekto pakitima
    git commit - m "zinute apibudinanti pakitima"

git push -> komanda, skirta paviesinti commit;us i atitinkama globalia saka

