 <h2>Unreal Engine 5 | Door & Light Interaction Systems </h2>
 
 Blueprint kullanılarak geliştirilmiş temel etkileşim sistemlerini içermektedir. Amacım, oyunlarda sık kullanılan kapı açma ve ışık açma-kapama mekaniklerini hem öğrenmek hem de uygulamaktı.

🎥 YouTube Tanıtım Videosu: https://www.youtube.com/watch?v=usBDRkUjaVQ

<h3>🔑 Kapı Açma Sistemi</h3>

Oyuncu kapıya yaklaştığında LineTrace ile oyuncu kapıyla etkileşime girer ve BP_Door tetiklenir.

<img width="1421" height="524" alt="Image" src="https://github.com/user-attachments/assets/6e717e09-61c9-4e4d-bcd3-694c3f98ee90" />


Kapı animasyonu, Timeline kullanılarak smooth (yumuşak) bir şekilde açılıp kapanır.

<img width="1070" height="549" alt="Image" src="https://github.com/user-attachments/assets/a6ecea15-1a17-4499-bdeb-a6024863493d" />


<h2>💡 Işık Açma Sistemi</h2>

<img width="1423" height="897" alt="Image" src="https://github.com/user-attachments/assets/330c161e-78f5-4461-9fdf-704ada970979" />


<img width="1444" height="902" alt="Image" src="https://github.com/user-attachments/assets/d32191b7-efab-4d54-9545-d956913bd88f" />

BP_LightOn blueprint’i içerisine eklenen Box Collision sayesinde, oyuncu alana girdiğinde ışık yanar, çıktığında otomatik olarak kapanır.

<img width="1412" height="820" alt="Image" src="https://github.com/user-attachments/assets/34221dd1-9300-4fe3-b676-41c360f5bdb2" />

<h4>🛠 Kullanılan Teknolojiler</h4>

 · Unreal Engine 5

 · Blueprint

 · LineTrace

 · Timeline

 · Box Collision
