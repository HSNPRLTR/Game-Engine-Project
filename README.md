TR

# Game-Engine-Project
Yaklaşık 3 haftalık bir süreçte, ilk kez öğrendiğim C++ diliyle sıfırdan bir 2D oyun motoru geliştirdim. Bu proje, Programlama Temelleri II dersi kapsamında dönem sonu proje ödevi olarak hazırladım.
Geliştirme sürecinde; tile tabanlı harita sistemi, katmanlı yapı, JSON formatında veri kaydı, camera system, bounding-box collision detection, ve kullanıcı girişlerini işleyen bir input-command sistemi gibi temel sistemler oluşturdum. 

Motor; Edit ve Play olmak üzere iki farklı moda sahip. Edit modunda tilemap düzenleyebilir, karakterleri sahneye yerleştirebilir ve çeşitli araçlarla düzenleme yapabilirsiniz. Play modunda ise bu sahne üzerinde oyun çalıştırılarak simülasyon test edilebilir. Yani motor, sadece düzenleme yapmaya değil, aynı zamanda oyunun sahne üzerinde oynanmasını simüle etmeye de olanak tanıyor. Geliştirilen kamera sistemi, oyun alanını dinamik olarak izlemeyi sağlarken; çarpışma tespiti, hareket fiziği, ve kullanıcı komutlarının işlenmesi gibi temel oyun mekaniği yapı taşlarını da entegre ettim.

Ayrıca motorun içinde component-based architecture benimsendi. Her oyun objesi (örneğin bir karakter, efekt ya da tile) farklı bileşenlerle tanımlandı. Bu sayede daha modüler ve esnek bir yapı elde edildi. Ek olarak Lua scripting desteği ile oyun objeleri dışarıdan script ile kontrol edilebilir hale geldi. Arayüz tarafında ise asset browser, inspector panel, karakter yerleştirme araçları ve modlar arası geçiş gibi işlevsel özellikler sunan sade ama kullanışlı bir editör tasarlandı. Basit bir kullanıcı doğrulama sistemi ve şifre maskeleme gibi özellikler de mevcut.

Kısacası, hem oyun editörü hem de çalışma ortamı sağlayan küçük çaplı ama oldukça kapsamlı bir 2D oyun motoru ortaya çıktı. Teknik olarak da mimari kurgu, veri yönetimi, input handling ve scripting gibi pek çok konuda bana deneyim kazandırdı.


EN

Over the course of approximately three weeks, I developed a 2D game engine entirely from scratch using C++, a programming language I was learning for the first time. This project was created as my final assignment for the *Programming Fundamentals II* course. During development, I implemented several core systems, including a tile-based map editor, a layered scene structure, JSON-based data serialization, a camera system, bounding-box collision detection, and an input-command system for processing user interactions.

The engine features two primary modes: **Edit Mode** and **Play Mode**. In Edit Mode, users can design tilemaps, place characters within the scene, and modify the environment using a variety of editing tools. In Play Mode, the created scene can be executed, allowing users to test gameplay directly within the engine. This enables the engine not only to function as a level editor but also as a complete environment for simulating and testing gameplay. In addition, I integrated a dynamic camera system, collision detection, movement mechanics, and user input handling, providing the essential building blocks of a functional game engine.

The engine also adopts a **component-based architecture**, where every game object—such as characters, visual effects, or tiles—is defined through reusable components. This design improves modularity, flexibility, and scalability. Furthermore, I added **Lua scripting** support, allowing game objects to be controlled externally through scripts. On the editor side, I designed a clean yet practical interface featuring an asset browser, inspector panel, character placement tools, and seamless switching between editing and gameplay modes. Additional features include a simple user authentication system and password masking functionality.

Overall, the project evolved into a compact yet feature-rich 2D game engine that combines both a level editor and a runtime environment. Beyond the final product itself, the development process provided valuable hands-on experience in software architecture, data management, input handling, scripting integration, and game engine design.
