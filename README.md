# Linux_TP6

-----

## Exercice 1: Hello, World!

* **Ouvrir un terminal puis taper dans votre terminal la commande suivante (le $ représente l’invite de commande, en anglais, le prompt, et il ne faut pas le taper) :**

![image](https://user-images.githubusercontent.com/91763346/205301787-bc50ba50-2861-4af3-bb35-eaa919a280a8.png)


* **Entrer la commande**

![image](https://user-images.githubusercontent.com/91763346/205301873-93409e7f-01e3-4eb7-b8d8-c721f895fa3e.png)


* **Entrer les commandes**

![image](https://user-images.githubusercontent.com/91763346/205301948-b3773e97-43bb-4728-b210-2cf19d7a9cc0.png)


* **Vous allez maintenant créer votre premier script shell. Placez-vous dans votre répertoire personnel en tapant cd puis entrée puis entrez la commande** 

![image](https://user-images.githubusercontent.com/91763346/205302400-eb8a1e09-c20c-417c-8d99-81bec6564552.png)


![image](https://user-images.githubusercontent.com/91763346/205302211-ee8e48c5-2bff-42e6-9077-4720a21f2064.png)

![image](https://user-images.githubusercontent.com/91763346/205302327-64e4e0c9-55af-4e49-b07c-619b3fb303f7.png)

![image](https://user-images.githubusercontent.com/91763346/205302525-8c1a10ad-5928-42aa-a56b-c511544fbdf3.png)

![image](https://user-images.githubusercontent.com/91763346/205302624-8d5019d3-a4fd-4405-8e5e-0fa9cb10e2c0.png)

# Exercice 2: Quelques variables d'environnement

Certaines variables, dîtes d’environnement sont automatiquement créées et transmises à tous vos shells (plus de précisions sur la notion de « variable d’environnement » dans un autre exercice). On peut citer par exemple (sans commentaire, le nom des variables parle de lui-même) :

— HOME
— PWD
— SHELL
— EDITOR

En vous servant de ces variables, écrire un script shell mes_infos
dans le répertoire ~/shell/tp5 dont la sortie ressemble à la suivante :

![image](https://user-images.githubusercontent.com/91763346/205303988-23800ec5-0a09-4eca-af33-9b6cc38e4d4e.png)

![image](https://user-images.githubusercontent.com/91763346/205304239-0198078d-9085-4cf1-a43c-b924c3a826ce.png)

## Exercice 3: Paramètres positionnels des scripts ( **Bash Scripting Arguments** )

* **Dans le répertoire ~/shell/tp5, saisir, enregistrer, et rendre exécutable le script param_pos suivant**

![image](https://user-images.githubusercontent.com/91763346/205305107-c48ae39a-167f-4224-8583-2108f0b23a56.png)

![image](https://user-images.githubusercontent.com/91763346/205305274-1849d57a-45fa-4142-a615-3875b2fa925a.png)


* **Entrer les commandes suivantes.**

```
./param_pos 45 aze oi

```

![image](https://user-images.githubusercontent.com/91763346/205309853-c1d0a446-d422-429f-9b2e-41a4eea0aba5.png)





```
$ ./param_pos
```

![image](https://user-images.githubusercontent.com/91763346/205310435-1527ed33-f098-4fd5-a37f-174c4cecf1a4.png)

```
$ ./param_pos L\’utilisateur $USER est\ un génie !
```

![image](https://user-images.githubusercontent.com/91763346/205310762-cb31922b-1a9f-41f2-af9f-46cb27e69032.png)


```
$ ./param_pos "L’utilisateur $USER est un génie !"
```

![image](https://user-images.githubusercontent.com/91763346/205311012-858fc6dd-2e6f-4496-b254-288eb1817949.png)


```
$ cd ~

```

![image](https://user-images.githubusercontent.com/91763346/205311294-ccdf5e48-97c5-4055-b7a4-ff5de325e21f.png)


```
$ ~/shell/tp4/param_pos 1 2 3
```

![image](https://user-images.githubusercontent.com/91763346/205311442-b0f1a660-49d9-4440-a76a-fd1ab965d000.png)


```
$ cd -
```

![image](https://user-images.githubusercontent.com/91763346/205311608-69646165-3094-4460-a851-bf9fec32ed77.png)


```
$ mv param_pos params
```

![image](https://user-images.githubusercontent.com/91763346/205311775-33858d4f-c434-40f3-a27a-2058f4f18547.png)


```
$ ./params {2..20}

```

![image](https://user-images.githubusercontent.com/91763346/205311886-031ebe20-412c-4adc-b2f1-863f4a27b3ec.png)



* **Faire le bilan.**




