TR

# Game Engine Project

Bu proje, **Programlama Temelleri II** dersi kapsamında geliştirdiğim ve yaklaşık **3 haftalık** bir süreçte, ilk kez öğrendiğim **C++** programlama diliyle tamamen sıfırdan oluşturduğum **2D oyun motorudur**. Projenin temel amacı yalnızca bir oyun geliştirmek değil, bir oyun motorunun temel yapı taşlarını anlayarak kendi editörümü ve çalışma ortamımı oluşturmaktı.

## Proje Hakkında

Oyun motoru; sahne düzenleme, oyun simülasyonu ve temel oyun sistemlerini tek bir uygulama altında birleştirecek şekilde tasarlanmıştır. Geliştirme sürecinde modern oyun motorlarında bulunan birçok temel sistem sıfırdan yazılmış ve birbirleriyle entegre edilmiştir.

Motor, hem oyun geliştirme hem de geliştirilen sahneyi çalıştırarak test etme imkanı sunmaktadır. Böylece kullanıcı, oluşturduğu seviyeleri aynı uygulama içerisinde düzenleyebilir ve anında oynatarak test edebilir.

## Özellikler

* Tile tabanlı harita sistemi
* Katmanlı (Layer) yapı
* JSON tabanlı veri kaydetme ve yükleme
* Dinamik kamera sistemi
* Bounding Box Collision Detection
* Input Command sistemi
* Hareket ve temel oyun fiziği
* Edit Mode ve Play Mode
* Karakter yerleştirme sistemi
* Asset Browser
* Inspector Panel
* Lua Script desteği
* Component-Based Architecture
* Basit kullanıcı doğrulama sistemi
* Şifre maskeleme özelliği

## Teknik Altyapı

* **Programlama Dili:** C++
* **Mimari:** Component-Based Architecture
* **Script Desteği:** Lua
* **Veri Formatı:** JSON
* **Editör Özellikleri:** Asset Browser, Inspector Panel, Tile Editor
* **Çarpışma Sistemi:** Bounding Box Collision Detection

## Geliştirme Süreci

Motor iki farklı çalışma moduna sahiptir:

### Edit Mode

Bu modda kullanıcı;

* Tilemap oluşturabilir ve düzenleyebilir,
* Karakterleri sahneye yerleştirebilir,
* Asset'leri yönetebilir,
* Inspector paneli üzerinden objeleri düzenleyebilir,
* Oyun sahnesini tasarlayabilir.

### Play Mode

Play Mode'a geçildiğinde oluşturulan sahne gerçek zamanlı olarak çalıştırılır ve oyun simüle edilir. Böylece geliştirilen seviyeler aynı uygulama içerisinde test edilebilir.

Bu süreçte kamera sistemi, hareket sistemi, çarpışma tespiti ve kullanıcı girişleri tamamen motor içerisinde işlenmektedir.

## Mimari Yapı

Projede **Component-Based Architecture** yaklaşımı kullanılmıştır.

Her oyun objesi (karakterler, efektler, tile'lar vb.) farklı bileşenlerden oluşturulmaktadır. Bu yapı sayesinde sistem daha modüler, yeniden kullanılabilir ve genişletilebilir hale gelmiştir.

Ayrıca eklenen **Lua Script** desteği sayesinde oyun objeleri dışarıdan script dosyalarıyla kontrol edilebilmektedir. Bu sayede motor yalnızca statik bir editör olmaktan çıkıp script tabanlı davranışların da geliştirilebildiği esnek bir yapıya dönüşmüştür.

## Bu Proje ile Kazandıklarım

Bu proje bana aşağıdaki konularda önemli deneyimler kazandırdı:

* C++ ile büyük ölçekli proje geliştirme
* Oyun motoru mimarisi
* Component-Based Architecture
* JSON veri yönetimi
* Input Handling
* Kamera sistemleri
* Çarpışma tespiti
* Lua Scripting entegrasyonu
* Editör geliştirme
* Veri yönetimi ve yazılım mimarisi

Bu proje sayesinde yalnızca bir oyun değil, oyunların geliştirilebileceği temel bir çalışma ortamı ve editör oluşturmuş oldum.

## Projeyi İndir

Projeyi incelemek veya çalıştırmak isterseniz aşağıdaki bağlantıyı kullanabilirsiniz.

**https://www.mediafire.com/file/0rkvr6tafg9ekez/my_game_engine.rar/file**



EN

# Game Engine Project

This project is a **2D game engine** developed entirely from scratch using **C++**, a programming language I learned for the first time, over a period of approximately **3 weeks**. It was created as the final project for the *Programming Fundamentals II* course. The main goal of this project was not only to build a game but also to understand the core structure of a game engine by designing both an editor and a runtime environment.

## About the Project

The engine was designed to combine level editing, game simulation, and core gameplay systems within a single application. During development, many fundamental systems found in modern game engines were implemented from scratch and integrated together.

The engine allows users to design levels, place objects, and immediately test them by running the created scene within the same application.

## Features

* Tile-based map system
* Layered architecture
* JSON-based save and load system
* Dynamic camera system
* Bounding Box collision detection
* Input Command system
* Movement and basic physics
* Edit Mode and Play Mode
* Character placement system
* Asset Browser
* Inspector Panel
* Lua scripting support
* Component-Based Architecture
* Basic user authentication system
* Password masking feature

## Technical Stack

* **Language:** C++
* **Architecture:** Component-Based Architecture
* **Scripting:** Lua
* **Data Format:** JSON
* **Editor Tools:** Asset Browser, Inspector Panel, Tile Editor
* **Collision System:** Bounding Box Collision Detection

## Development Process

The engine includes two main modes:

### Edit Mode

In Edit Mode, users can:

* Create and edit tilemaps
* Place characters into the scene
* Manage assets
* Modify objects using the Inspector panel
* Design complete game levels

### Play Mode

In Play Mode, the created scene runs in real time, allowing users to test gameplay directly within the engine. This enables rapid iteration and immediate testing of designed levels.

Core systems such as camera control, movement, collision detection, and input handling are fully processed within the engine itself.

## Architecture

The project follows a **Component-Based Architecture** approach.

Each game object (such as characters, effects, or tiles) is composed of multiple reusable components. This design makes the system modular, flexible, and easily extendable.

In addition, **Lua scripting support** was integrated, allowing game objects to be controlled externally via scripts. This transforms the engine from a static editor into a flexible system capable of supporting dynamic behavior.

## What I Learned

This project provided me with valuable experience in:

* Large-scale C++ development
* Game engine architecture
* Component-Based design
* JSON data management
* Input handling systems
* Camera systems
* Collision detection
* Lua scripting integration
* Editor development
* Software architecture and system design

Through this project, I built not only a game but also a complete environment for creating and testing games.

## Download

You can download and explore the project using the link below:

**https://www.mediafire.com/file/0rkvr6tafg9ekez/my_game_engine.rar/file**

