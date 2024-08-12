# Introduction

Cette traduction est pour le moment une traduction brute de [learn-wgpu](https://sotrh.github.io/learn-wgpu/) par [sorth](https://github.com/sotrh). J'ajouterai à l'avenir mes propres commentaires ou tutoriels pour venir compléter ce tutoriel. Ma traduction sera plutôt franglaise dû au fait que je considère que certains termes ont plus de sens en anglais qu'en français tel que bindings.

## WGPU, c'est quoi ?

[Wgpu](https://github.com/gfx-rs/wgpu) est une implémentation en Rust de [WebGPU API spec](https://gpuweb.github.io/gpuweb/). WebGPU est une spécificaton publiée par GPU for the Web Community Group. Il vise à permettre au code web d'accéder aux fonctions du GPU de manière sûre et fiable. Pour ce faire, il imite l'API Vulkan et la traduit dans l'API utilisée par le matériel hôte (ie. DirectX, Metal, Vulkan).

Wgpu est encore en cours de développement, donc certains éléments de ce document sont susceptibles d'être modifiés.

## Pourquoi Rust ?

Wgpu à des bindings C qui vous permet d'écrire en C/C++, ainsi que d'autres langages qui s'interfaces avec le C. Cependant, wgpu est écrit en Rust, et il dispose de liens Rust pratiques qui évitent les obstacles. De plus j'ai pris beaucoup de plaîsir à programmer en Rust. 

Avant de commencer ce tutoriel assurez vous d'être familié avec Rust car je n'irais pas dans le détail au sujet de la syntaxe Rust. Si vous n'êtes pas à l'aise avec Rust vous pouvez suivre ce [Tutoriel Rust](https://www.rust-lang.org/learn). Vous devez être aussi familiarisé avec [Cargo](https://doc.rust-lang.org/cargo/).

J'utilise ce projet pour apprendre moi même wgpu, donc il se peut que certaines informations soient manquantes, ou mals expliquées. Je suis toujours ouvert aux retours constructifs.

## Contribution et Support

* J'accepte les pull requests ([GitHub repo](https://github.com/sotrh/learn-wgpu)) pour résoudre les problèmes de ce tutoriel, tels que les fautes de frappe, les informations incorrectes et autres incohérences.
* Due aux changements réguliers de l'api de wgpu, je n'accepte pas les pulls requests de démos.
* Si vous voulez me soutenir directement, rendez vous sur mon [patreon](https://www.patreon.com/sotrh)!

## Traduction

* [中文版: 增加了与 App 的集成与调试系列章节](https://jinleili.github.io/learn-wgpu-zh/)
* [Version française](TODO)

## Remerciements spécials à ces patrons

* David Laban
* yutani
* Gunstein Vatnar
* Lennart
* Paul E Hansen
* Eliot Bolduc
* Ian Gowen
* Ben Anderson
* Aron Granberg
* Ken K
* Bernard Llanos
* Danny McGee
* Thunk
* Zeh Fernando
* Craft Links
* Felix
* Youngsuk Kim
* Tema
* オリトイツキ
* Andrea Postal
* Davide Prati
* 大典 加藤
* charlesk
* Julius Liu
* Feng Liang
* dadofboi
* Mattia Samiolo
* Jani Turkia
* papyDoctor
* Filip
* Alexander Kabirov
* Nico Arbogast
* Dude
* Georeth Zhow
* Lions Heart
* Ryan
