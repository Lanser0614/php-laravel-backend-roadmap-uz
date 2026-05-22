# PHP / Laravel Backend Developer Roadmap

Bu hujjat PHP / Laravel backend developer sifatida rivojlanish uchun kerakli yo‘nalishlar, kurslar, kitoblar va amaliy resurslarni tartibli ko‘rinishda jamlaydi.

## Mundarija

- [1. Asosiy developer tools](#1-asosiy-developer-tools)
- [2. Umumiy roadmap](#2-umumiy-roadmap)
- [3. Linux](#3-linux)
- [4. PHP 7.x / 8.x](#4-php-7x--8x)
- [5. OOP in PHP](#5-oop-in-php)
- [6. Laravel Framework](#6-laravel-framework)
- [7. Databases](#7-databases)
- [8. Clean Code va Architecture](#8-clean-code-va-architecture)
- [9. Design Patterns](#9-design-patterns)
- [10. Docker va Kubernetes](#10-docker-va-kubernetes)
- [11. Unit Testing va Code Quality](#11-unit-testing-va-code-quality)
- [12. DDD, Microservices va Event Driven Architecture](#12-ddd-microservices-va-event-driven-architecture)
- [13. Deep Dive Tooling](#13-deep-dive-tooling)
- [14. Kafka](#14-kafka)
- [15. Algorithms & Data Structures](#15-algorithms--data-structures)
- [16. System Design](#16-system-design)
- [17. Computer Science bazasi](#17-computer-science-bazasi)
- [18. Kompetensiyalar jadvali](#18-kompetensiyalar-jadvali)

---

## 1. Asosiy Developer Tools

Developer sifatida ishlash uchun birinchi navbatda quyidagi bazaviy tool’larni yaxshi bilish kerak.

### IDE va Editorlar

- [Mastering PhpStorm](https://coursehunter.net/course/osvoenie-phpstorm)
- [Vim Cheatsheet](https://vim.rtorr.com/)
- [Learn Vim](https://github.com/iggredible/Learn-Vim)

### Terminal

- Terminal / iTerm
- oh-my-zsh

### Version Control

- Git
- GitHub
- GitLab

> Git bo‘yicha internetdagi istalgan yaxshi bazaviy materialdan foydalanish mumkin.

### Docker

- Docker
- Docker Desktop

### Architecture Decision Records

- [ADR GitHub Repository](https://github.com/joelparkerhenderson/architecture-decision-record)

---

## 2. Umumiy Roadmap

Backend va PHP bo‘yicha umumiy o‘rganish yo‘nalishlari:

- [Backend Developer Roadmap](https://roadmap.sh/backend)
- [PHP Roadmap](https://github.com/MaksimDzhangirov/PHP-roadmap)

---

## 3. Linux

Backend developer uchun Linux terminal, filesystem, permissions, processlar va shell script asoslarini bilish muhim.

### Kurslar

- [Linux asoslari](https://coursehunter.net/course/osnovy-linux)
- [Linux tayyorlov kursi](https://coursehunter.net/course/podgotovitelnyy-kurs-linux)

### Qo‘llanmalar

- [Losst.pro](https://losst.pro/)
- [HackerRank Shell Practice](https://www.hackerrank.com/domains/shell)

### Eng ko‘p ishlatiladigan commandlar

- [101 Bash Commands](https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je#the-basics)
- [101 Linux Commands](https://linuxhint.com/101-linux-commands/#27)

---

## 4. PHP 7.x / 8.x

PHP backend development uchun til sintaksisi, OOP, typing, error handling, Composer, autoloading va ecosystem’ni chuqur tushunish kerak.

### Amaliy o‘rganish

- [Exercism PHP](https://exercism.org/dashboard)
- [Code.mu PHP Book](https://code.mu/ru/php/book/prime/)
- [Codecademy PHP](https://www.codecademy.com/catalog/language/php)
- [PHP Tutorial](https://www.phptutorial.net/)

### Best Practices

- [PHP The Right Way](https://phptherightway.com/)
- [Clean Code PHP](https://github.com/piotrplenik/clean-code-php)
- [Awesome PHP](https://gist.github.com/llbbl/7607016)

### Kurslar va video materiallar

- [PHP 8: To‘liq qo‘llanma](https://coursehunter.net/course/php8-polnoe-rukovodstvo)
- [Dmitriy Eliseev — HTTP Framework yozish](https://www.youtube.com/watch?v=w4iqxN0nfTs&list=PLE20id3DjfFnio1Sm7WFOThtfqDGQdJgU)

### Chuqur o‘rganish

- Modern PHP — Josh Lockhart
- [PHP Internals Book](https://www.phpinternalsbook.com/)
- [Zend PHP Certification](https://github.com/ivantusek/Zend-PHP-Certification/tree/master)

### Code Quality Tools

- [PHPStan](https://github.com/phpstan/phpstan)
- [PHP-CS-Fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer)
- [Rector](https://github.com/rectorphp/rector)
- [Rector kitobi](https://coursehunter.net/book/rector-sila-avtomatizirovannogo-refaktoringa)

---

## 5. OOP in PHP

Object-Oriented Programming backend development’ning asosiy fundamentlaridan biri hisoblanadi.

### Kurslar

- [Dmitriy Eliseev — OOP](https://coursehunter.net/course/nedelya-oop-tretiy-potok)
- [Bugaenko — OOP haqida](https://www.youtube.com/watch?v=lfdAwl3-X_c)

### Kitoblar

- PHP Objects and Patterns

---

## 6. Laravel Framework

Laravel bilan ishlaganda framework’ning ichki mexanizmlari, queue, event, service container, Eloquent, migration, testing va deployment jarayonlarini yaxshi bilish kerak.

### Laravel asoslari

- [Dmitriy Eliseev — Laravel Master Class](https://coursehunter.net/course/master-klass-po-laravel)
- [Afanasyev Laravel Playlist](https://www.youtube.com/playlist?list=PLoonZ8wII66iP0fJPHhkLXa3k7CMef9ak)
- [Laracasts](https://laracasts.com/)
- [Laravel Daily](https://laraveldaily.com/)
- [Laravel Daily CourseHunter](https://coursehunter.net/source/laraveldaily-com)

### Queue va Scaling

- [Laravel Queue YouTube](https://www.youtube.com/watch?v=J895Bzwf_0U)
- [Laravel Scaling](https://coursehunter.net/course/masshtabirovanie-laravel)

### Laravel Architecture

- [OOP + DDD in Laravel](https://coursehunter.net/book/predmetno-orientirovannoe-proektirovanie-s-laravel)
- [Laravel Beyond CRUD](https://coursehunter.net/book/kniga-video-laravel-za-predelami-crud)
- [Microservices with Laravel](https://coursehunter.net/book/mikroservisy-s-laravel)
- [Ready Laravel](https://coursehunter.net/book/gotovyy-k-boyu-laravel)
- [Laravel Concepts](https://coursehunter.net/book/koncepcii-laravel)

### DevOps va Performance

- [DevOps with Laravel](https://coursehunter.net/book/devops-s-laravel)
- [Laravel Performance](https://coursehunter.net/book/proizvoditelnost-s-laravel)

### Bloglar

- [Martin Joo Blog](https://martinjoo.dev/blog)

---

## 7. Databases

Backend developer SQL, indexing, transactions, isolation levels, query optimization va database design asoslarini bilishi kerak.

### SQL Practice

- [Codecademy SQL](https://www.codecademy.com/catalog/language/sql)
- [SQL Zoo](https://sqlzoo.net/wiki/SQL_Tutorial)
- [SQL Bolt](https://sqlbolt.com/)
- [HackerRank SQL](https://www.hackerrank.com/domains/sql)

### MySQL

- [MySQL Tutorial](https://www.mysqltutorial.org/)
- [MySQL Bootcamp](https://coursehunter.net/course/mysql-bootcamp-sql-ot-novichka-k-ekspertu)
- [MySQL Essential](https://coursehunter.net/course/mysql-essential)

### PostgreSQL

- [SQL va PostgreSQL beginner course](https://coursehunter.net/course/prakticheskiy-kurs-dlya-novichkov-po-sql-i-postgresql)
- [SQL va PostgreSQL to‘liq qo‘llanma](https://coursehunter.net/course/sql-i-postgresql-polnoe-rukovodstvo-razrabotchika)

### MongoDB

- [MongoDB Full Guide](https://coursehunter.net/course/polnoe-rukovodstvo-dlya-razrabotchika-po-mongodb)

---

## 8. Clean Code va Architecture

Kod sifati, arxitektura va refactoring uzoq muddatli loyihalar uchun juda muhim.

### Architecture

- [Porto Architecture](https://github.com/Mahmoudz/Porto)
- [Afanasyev Porto Playlist](https://www.youtube.com/playlist?list=PLoonZ8wII66jR2ZN8B3p5VoScojQ-Zn2Q)

### Kitoblar

- Robert C. Martin — Clean Code
- Robert C. Martin — Clean Architecture
- Martin Fowler — Refactoring

### Refactoring

- [Refactoring Guru](https://refactoring.guru/ru/refactoring/course)

---

## 9. Design Patterns

Design pattern’lar murakkab biznes logic’ni toza va kengaytiriladigan qilishga yordam beradi.

### Kurslar

- [GRASP and GoF Design Patterns](https://coursehunter.net/course/grasp-and-gof-design-patterns-advanced-on-line-course)
- [Enterprise Patterns](https://coursehunter.net/course/enterprise-patterns)

### Video materiallar

- [Afanasyev Design Patterns 1](https://www.youtube.com/playlist?list=PLoonZ8wII66hKbEvIVAZnp1h4CE-4Mtk4)
- [Afanasyev Design Patterns 2](https://www.youtube.com/playlist?list=PLoonZ8wII66jy3Mazkks_I1Eg30gdee2k)
- [Christopher Okhravi](https://www.youtube.com/@ChristopherOkhravi/playlists)

### Qo‘llanmalar

- [Refactoring Guru Design Patterns](https://refactoring.guru/ru/design-patterns/book)
- [Design Patterns PHP](https://designpatternsphp.readthedocs.io/en/latest/)

---

## 10. Docker va Kubernetes

Production environment’ga yaqin ishlash uchun containerization va orchestration asoslarini bilish kerak.

### Practice

- [Play with Docker](https://labs.play-with-docker.com/)
- [Play with Kubernetes](https://labs.play-with-k8s.com/)

### Docker

- [Docker for PHP Developers](https://coursehunter.net/course/docker-dlya-razrabotchikov-php)
- [Docker, Ansible, Swarm](https://coursehunter.net/course/docker-ansible-s-nulya-deploy-i-upravlenie-swarm)

### Kubernetes

- [Nana Kubernetes Intro](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [Docker va Kubernetes to‘liq qo‘llanma](https://coursehunter.net/course/docker-i-kubernetes-polnoe-rukovodstvo)
- [Kubernetes va Helm](https://coursehunter.net/course/kubernetes-i-helm)
- [Kubernetes for Developers](https://coursehunter.net/course/kubernetes-dlya-razrabotchikov)
- [Laravel in Kubernetes](https://chris-vermeulen.com/laravel-in-kubernetes/)

### Certification

- [CKAD](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/)
- [Docker Certified Associate](https://store.mirantis.com/product/docker-certified-associate-dca/)

### Qo‘shimcha

- [KodeKloud](https://learn.kodekloud.com/user/dashboard)

---

## 11. Unit Testing va Code Quality

Test yozish production bug’larni kamaytiradi va refactoring jarayonini xavfsizroq qiladi.

### Laravel Testing

- [Laravel PHPUnit for Beginners](https://coursehunter.net/course/laravel-phpunit-testirovanie-dlya-nachinayushchih)
- [Confident Laravel](https://coursehunter.net/course/uverennyy-laravel-ot-otsutstviya-testov-do-uverennyh-prilozheniy)

---

## 12. DDD, Microservices va Event Driven Architecture

Katta tizimlarda domain modeling, service boundaries, event-driven communication va async processing muhim rol o‘ynaydi.

### DDD va Software Architecture

- [Awesome DDD](https://github.com/heynickc/awesome-ddd)
- [Awesome Software Architecture](https://github.com/mehdihadeli/awesome-software-architecture)
- [DDD o‘rganish rejasi](https://habr.com/ru/articles/653421/)
- [Arkency Blog](https://blog.arkency.com/)

### Microservices

- [Microservices Intro](https://www.youtube.com/watch?v=eI1QQUrFUZI)
- Chris Richardson — Microservices Patterns
- [Microservices Patterns and Practice](https://coursehunter.net/course/microservices-patterny-i-praktika-postroeniya-mikroservisov)
- [Microservices with Laravel](https://coursehunter.net/book/mikroservisy-s-laravel)

### Event Driven / Async Architecture

- [Event Sourcing, CQRS, DDD](https://coursehunter.net/course/prilozheniya-s-ispolzovaniem-event-sourcing-cqrs-ddd)
- [Async Architecture](https://coursehunter.net/course/asinhronnaya-arhitektura)
- [Software Architecture Roadmap](https://roadmap.sh/software-design-architecture)
- [Lucid Architecture](https://lucidarch.dev/)
- [Architecture Modernization](https://www.youtube.com/watch?v=Ls3XnV3BIyU)

### Event Storming

- [Dmitriy Eliseev — Event Storming](https://deworker.pro/edu/series/event-storming)
- [Event Storming Video 1](https://www.youtube.com/watch?v=kJjuTuviZ-E)
- [Event Storming Video 2](https://www.youtube.com/watch?v=mLXQIYEwK24)
- [Event Storming Video 3](https://www.youtube.com/watch?v=NSN-NXfbEqM)
- [Event Storming Video 4](https://www.youtube.com/watch?v=n2RFyLi0sgc)
- [DDD for Microservices](https://medium.com/@chatuev/ddd-for-microservices-4778a363c071)
- [Big Picture Event Storming](https://medium.com/@chatuev/big-picture-event-storming-7a1fe18ffabb)

---

## 13. Deep Dive Tooling

Bu mavzularni alohida chuqur o‘rganish tavsiya qilinadi:

- WebSocket / Centrifugo
- ELK Stack
- Grafana Stack
- Object Storage / MinIO
- Tracing / Jaeger
- Full-text search:
  - Elasticsearch
  - Algolia
  - Meilisearch

---

## 14. Kafka

Kafka event-driven architecture, async processing, event sourcing va distributed systems uchun muhim texnologiyalardan biri.

### Documentation

- [Kafka Official Documentation](https://kafka.apache.org/documentation/)
- [Confluent Kafka Quickstart](https://developer.confluent.io/quickstart/kafka-on-confluent-cloud/)
- [Event Driven vs State Based](https://developer.confluent.io/courses/event-sourcing/event-driven-vs-state-based/)

### Kurslar

- [Apache Kafka](https://coursehunter.net/course/apache-kafka)
- [Dmitriy Eliseev — Kafka va RabbitMQ](https://coursehunter.net/course/master-klass-po-apache-kafka-i-rabbitmq)

### Laravel Kafka

- [Laravel Kafka Docs](https://laravelkafka.com/docs/v2.0/introduction)

### Tools

- [Kafka UI](https://github.com/provectus/kafka-ui)
- [Kafka with Docker](https://jaehyeon.me/series/kafka-development-with-docker/)
- [Kafka Medium Articles](https://medium.com/@Irori)

---

## 15. Algorithms & Data Structures

Algorithms va data structures intervyu, problem solving va performance optimizatsiya uchun kerak.

### Kurslar

- [Algorithms and Data Structures](https://coursehunter.net/course/podgotovka-k-sobesedovaniyu-algoritmy-i-struktury-dannyh)
- [AlgoExpert](https://coursehunter.net/course/algoexpert-stante-ekspertom-po-algoritmam)
- [Vlad Ten — Algorithms from Zero](https://coursehunter.net/course/algoritmy-s-nulya)

### Practice

- [LeetCode](https://leetcode.com/problemset/)
- [Codeforces](https://codeforces.com/)

---

## 16. System Design

System Design katta tizimlarni loyihalash, scaling, caching, queue, database sharding, consistency va reliability mavzularini qamrab oladi.

### Resources

- [ByteByteGo](https://bytebytego.com/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/)
- [Karpov System Design](https://coursehunter.net/course/system-design-proektirovanie-sistem)
- [Educative — Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview)

---

## 17. Computer Science bazasi

Backend engineer uchun faqat framework bilish yetarli emas. Computer systems, OS, networking, DB, distributed systems va security asoslari ham kerak.

### Computer Systems

- [Vlad Ten — Bazaviy bilimlar](https://youtu.be/fW_imcrTA_c?si=KU0S22DZzgvLN9Dd)
- [Computer Systems Playlist](https://www.youtube.com/watch?v=Keducx5bp-g&list=PL0j-r-omG7i0-mnsxN5T4UcVS1Di0isqf&index=17)
- [Nand2Tetris](https://www.nand2tetris.org)

### Operating Systems

- [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [Wisconsin OS Course](https://pages.cs.wisc.edu/~remzi/Classes/537/Fall2021/)
- [MIT 6.S081](https://pdos.csail.mit.edu/6.S081/2021/schedule.html)

### Algorithms

- [MIT Algorithms](https://www.youtube.com/watch?v=oFVYVzlvk9c&list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY&index=13)

### Math

- [3Blue1Brown](https://www.3blue1brown.com/#lessons)
- [MIT OCW](https://ocw.mit.edu/course-lists/scholar-courses/)
- [Khan Academy](https://www.khanacademy.org)
- [Math Academy](https://mathacademy.com/adult-students)

### Networking

- [Kurose & Ross Wireshark](http://gaia.cs.umass.edu/kurose_ross/wireshark.php)
- [Networking Playlist](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0NS)

### Databases

- [CMU 15-445](https://15445.courses.cs.cmu.edu/fall2024/assignments.html)
- [Database Systems Playlist](https://www.youtube.com/watch?v=niLwbfE3V9Q&list=PLSE8ODhjZXjYDBpQnSymaectKjxCy6BYq&index=20)

### Distributed Systems

- [MIT 6.824](https://pdos.csail.mit.edu/6.824/schedule.html)
- [Distributed Systems Playlist](https://www.youtube.com/watch?v=UEAMfLPZZhE&list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB)

### Security

- [Stanford CS253](https://web.stanford.edu/class/cs253/)
- [MIT Security](https://61600.csail.mit.edu/2023/)

---

## 18. Kompetensiyalar jadvali

Developer kompetensiyalarini tekshirish va o‘sish yo‘nalishlarini ko‘rish uchun:

- [Google Sheets — Kompetensiyalar jadvali](https://docs.google.com/spreadsheets/d/1mblKZrIhZMGFCn02LVyKSgk8gish_VKB4Dsva0ZadOE/edit?usp=sharing)

---

## Tavsiya qilingan o‘rganish tartibi

Agar noldan yoki junior/middle darajadan boshlasangiz, quyidagi tartibda o‘rganish qulay bo‘ladi:

1. Developer tools: PhpStorm, Git, Terminal, Docker
2. Linux basics
3. PHP syntax, OOP, Composer
4. Laravel basics
5. SQL va database design
6. Laravel queue, events, jobs
7. Testing va code quality tools
8. Clean Code va Design Patterns
9. Docker, Kubernetes, CI/CD
10. DDD, Microservices, Event Driven Architecture
11. Kafka va async systems
12. System Design
13. Computer Science fundamentals

---

## Eslatma

Bu roadmap bir kunda tugatiladigan ro‘yxat emas. Uni bosqichma-bosqich o‘rganish kerak. Eng yaxshi yondashuv:

- Har bir mavzuni kichik project orqali mustahkamlash
- O‘rgangan narsani real code’da ishlatish
- Documentation o‘qishga odatlanish
- Code review va refactoring qilish
- Production muammolarini tahlil qilish
