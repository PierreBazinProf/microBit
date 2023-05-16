# Niveau 1 

# Tutoriel 2 

## @showdialog 

But du projet => Programme le micro:bit pour qu'il affiche ton prénom lorsque le bouton A est pressé. 

## Étape 1 

Supprime les blocs ``||basic:au démarrage||`` et ``||basic:toujours||``. 

## Étape 2 

Ajoute le bloc ``|| basic: afficher texte ||`` dans le bloc ``||input:lorsque le bouton A est pressé||``. 

```blocks 

input.onButtonPressed(Button.A, function () {
    basic.showString("Hello!")
})

``` 

## Étape 3 


Efface le mot ``|| basic: Hello! ||`` du bloc ``|| basic: afficher texte ||``. 

 

Écris ton prénom dans le bloc ``|| basic: afficher texte ||`` (ex. : Pierre). 

 

```blocks 

input.onButtonPressed(Button.A, function () {
    basic.showString("Pierre")
})

``` 

## Étape 4 

Ajoute le bloc ``|| basic: afficher texte ||`` dans le bloc ``||input:lorsque le bouton B est pressé||``. 

```blocks 

input.onButtonPressed(Button.B, function () {
    basic.showString("Hello!")
})

``` 

## Étape 5 


Efface le mot ``|| basic: Hello! ||`` du bloc ``|| basic: afficher texte ||``. 

 

Écris ton nom de famille dans le bloc ``|| basic: afficher texte ||`` (ex. : Bazin). 



```blocks 

input.onButtonPressed(Button.B, function () {
    basic.showString("Bazin")
})

``` 

 

## Étape 6

 Ajoute le bloc ``|| basic: montrer l'icône ||`` dans le bloc ``||input:lorsque le bouton A+B est pressé||``. 

Choisis l'icône de ton choix. 

```blocks 

input.onButtonPressed(Button.AB, function () {
    basic.showIcon(IconNames.Happy)
})


``` 

## @showdialog 

Télécharge le programme dans le micro:bit. 

 Teste le programme! 

 