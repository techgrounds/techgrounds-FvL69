## LINUX-02:

Het Linux file systeem is een omgekeerde boom. Het start bij / (root) en breidt
zich verder naar beneden uit met directories die files en subdirectories bevatten enz...

## KEY-TERMS:

Root = het begin van het file systeem

**commands:**

MKDIR = creëer een nieuwe directory

TOUCH = creëer een nieuwe file

CD = change directory

CAT = concatenate file 

PWD = present working directory

## OPDRACHT:

**Exercise:**
* ● Find out your current working directory.
* ● Make a listing of all files and directories in your home directory.
* ● Within your home directory, create a new directory named ‘techgrounds’.
* ● Within the techgrounds directory, create a file containing some text.
* ● Move around your directory tree using both absolute and relative paths.

## ERVAREN PROBLEMEN:
Geen.

## RESULTAAT:
![PrtSc result](../00_includes/week1/Linux/2023-06-06_3.png)

**Inloggen bij AWS Linux server in PowerShell:**
ssh -p 52201 -i Nest-fr-van-Lieshout.pem francois_@3.121.130.219

**Gebruikte commandos in de opdracht:**

pwd = current working directory

ll = alias for ls -la

mkdir techgrounds = nieuwe dir met de naam techgrounds gecreëerd

cd techgrounds = change to directory techgrounds

cat = concatenate file

cat > 'filename' = redirect to file

cd / = absolute path naar root

cd ../.. = relative path naar root

cd /home/ = absolute path naar home directory

cd ~ change directory to francois directory (home dir)


