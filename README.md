# PROYECTO-ANDROID
[codificacion karol.pdf](https://github.com/user-attachments/files/26194476/codificacion.karol.pdf)

Codificación: 
res/ 
├─ values/            
├─ values-en/         
├─ values-fr/        
├─ values-de/         
→ Español (default) 
→ Inglés 
 → Francés 
→ Alemán 
res/values/strings.xml (Español) 
<resources> 
<string name="app_name">Mi Proyecto</string> 
<string name="welcome">Bienvenido</string> 
</resources> 
res/values-en/strings.xml 
<resources> 
<string name="app_name">My Project</string> 
<string name="welcome">Welcome</string> 
</resources> 
res/values-fr/strings.xml 
<resources> 
<string name="app_name">Mon Projet</string> 
<string name="welcome">Bienvenue</string> 
</resources> 
res/values-de/strings.xml 
<resources> 
<string name="app_name">Mein Projekt</string> 
<string name="welcome">Willkommen</string> 
</resources> 
<img width="348" height="529" alt="image" src="https://github.com/user
attachments/assets/074b7647-969e-4350-937f-8c3910186bae" /> 
<img width="353" height="524" alt="image" src="https://github.com/user
attachments/assets/89b6a28a-2bc1-4628-bd0c-a92b65095273" /> 
<img width="530" height="352" alt="image" src="https://github.com/user
attachments/assets/d1760587-ea70-4fb6-bdf9-3acc0cfb0a94" /> 
<img width="525" height="348" alt="image" src="https://github.com/user
attachments/assets/0ec01f4f-e16f-482f-86e1-6ca35e4f8a73" /> 
<img width="693" height="430" alt="image" src="https://github.com/user
attachments/assets/0f6a1393-fa98-4c25-9270-5585e9810b37" /> 
res/layout/activity_main.xml 
<ConstraintLayout 
xmlns:android="http://schemas.android.com/apk/res/android" 
xmlns:app="http://schemas.android.com/apk/res-auto" 
android:layout_width="match_parent" 
android:layout_height="match_parent" 
android:background="@drawable/fondo"> 
<TextView 
android:id="@+id/texto" 
android:layout_width="wrap_content" 
android:layout_height="wrap_content" 
android:text="@string/welcome" 
android:textSize="24sp" 
android:textColor="#FFFFFF" 
app:layout_constraintTop_toTopOf="parent" 
app:layout_constraintBottom_toBottomOf="parent" 
app:layout_constraintStart_toStartOf="parent" 
app:layout_constraintEnd_toEndOf="parent"/> 
</ConstraintLayout> 
Crear layouts alternativos: 
res/layout/             
res/layout-land/           
res/layout-sw600dp/        
   → móviles 
→ horizontal 
→ tablets

![WhatsApp Image 2026-03-23 at 12 37 58 PM](https://github.com/user-attachments/assets/01d74464-8829-4f10-ac5c-ec5314f7c137)
![WhatsApp Image 2026-03-23 at 12 37 44 PM](https://github.com/user-attachments/assets/15d43925-da6f-4095-9ad8-27723327e530)
![WhatsApp Image 2026-03-23 at 12 37 29 PM](https://github.com/user-attachments/assets/85aae6f5-c281-4a87-ae70-7293eec939dd)
![WhatsApp Image 2026-03-23 at 12 36 43 PM](https://github.com/user-attachments/assets/c2af3064-b522-4507-83f5-03b236a7e1fe)


