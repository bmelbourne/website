---
title: Пространство имен
id: namespace
date: 2018-04-12
full_link: /docs/concepts/overview/working-with-objects/namespaces
short_description: >
  Абстракция, которую Kubernetes использует для изоляции групп ресурсов в рамках одного кластера.

aka: 
tags:
- fundamental
---
 Абстракция, которую Kubernetes использует для изоляции групп ресурсов в рамках одного {{< glossary_tooltip text="кластера" term_id="cluster" >}}.

<!--more--> 

Пространства имен используются для организации объектов в кластере и разграничивают ресурсы кластера. Имена ресурсов должны быть уникальными в пределах одного пространства имен, но не в разных пространствах имен. Ограничения на основе пространства имен применимы только к объектам на уровне пространств имен _(например, Deployments, Services и т.д.)_, но не для объектов на уровне кластера _(таких как StorageClass, Nodes, PersistentVolumes и т.д.)_.