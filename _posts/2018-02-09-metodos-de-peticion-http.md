---
title: Métodos de petición HTTP
layout: post
date: '2018-02-09 22:16:21'
categories: api
author: Paulo McNally
---

HTTP define un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs. Cada uno de ellos implementan una semántica diferente, pero algunas características similares son compartidas por un grupo de ellos: ej. un request method puede ser safe, idempotent, o cacheable.

## GET
El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.

## HEAD
El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.

## POST
El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.

## PUT
El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.

## DELETE
El método DELETE borra un recurso en específico.

## CONNECT
El método CONNECT establece un tunel hacia el servidor identificado por el recurso.

## OPTIONS
El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.

## PATCH
El método PATCH  es utilizado para aplicar modificaciones parciales a un recurso.

**Fuente**:
* [https://developer.mozilla.org/es/docs/Web/HTTP/Methods](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)