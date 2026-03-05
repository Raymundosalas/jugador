# Videojuego 2D en Unity – Implementación de Prefabs

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un videojuego en 2D utilizando el motor gráfico Unity. El objetivo de la actividad es comprender el uso de **Prefabs**, que son objetos reutilizables dentro de Unity y permiten optimizar el desarrollo de videojuegos.

En este proyecto se implementaron distintos elementos del juego como el **jugador, enemigos, monedas y plataformas**, los cuales fueron convertidos en Prefabs para poder reutilizarlos en diferentes escenas del juego.

## Objetivo

Desarrollar un prototipo básico de videojuego en 2D en Unity que incluya la creación y uso de Prefabs, así como la implementación de scripts en C# para controlar el comportamiento de los objetos del juego.

## Características del videojuego

* Movimiento del personaje principal.
* Sistema de salto del jugador.
* Enemigos con movimiento automático.
* Monedas coleccionables.
* Sistema básico de puntuación.
* Uso de Prefabs reutilizables.

## Prefabs implementados

En el proyecto se crearon los siguientes Prefabs:

* **Player** – Personaje controlado por el jugador.
* **Enemy** – Enemigos con movimiento automático.
* **Coin** – Objetos coleccionables.
* **Ground** – Plataforma o suelo del juego.

Estos Prefabs permiten reutilizar los objetos dentro de la escena sin tener que configurarlos nuevamente.

## Scripts utilizados

El proyecto incluye los siguientes scripts desarrollados en C#:

* **PlayerMovement.cs**
  Permite el movimiento del jugador hacia la izquierda y derecha, así como el salto.

* **EnemyMovement.cs**
  Controla el movimiento automático de los enemigos dentro del escenario.

* **EnemyDamage.cs**
  Detecta la colisión entre el jugador y el enemigo.

* **Coin.cs**
  Permite recolectar monedas cuando el jugador entra en contacto con ellas.

* **GameManager.cs**
  Administra el sistema de puntuación del juego.

## Estructura del proyecto

Assets
│
├── Scenes
│   MainScene.unity
│
├── Scripts
│   PlayerMovement.cs
│   EnemyMovement.cs
│   EnemyDamage.cs
│   Coin.cs
│   GameManager.cs
│
├── Prefabs
│   Player.prefab
│   Enemy.prefab
│   Coin.prefab
│   Ground.prefab

## Tecnologías utilizadas

* Unity (Motor de desarrollo de videojuegos)
* C#
* Visual Studio / Visual Studio Code
* GitHub

## Repositorio

En este repositorio se encuentra el proyecto completo del videojuego desarrollado en Unity con la implementación de Prefabs.

## Autor

Raymundo Salas Rodríguez

