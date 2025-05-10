# UTS_Pemograman-Mobile-1_M.-Fikri-Nasrulloh
Source code Project 
''' splashscreenactivity.xml

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">


 <ImageView
     android:id="@+id/splashscreen"
     android:layout_width="match_parent"
     android:layout_height="match_parent"
     android:scaleType="centerCrop"
     android:src="@drawable/splashscreen"
     app:layout_constraintEnd_toEndOf="parent"
     tools:layout_editor_absoluteY="0dp"/>



</androidx.constraintlayout.widget.ConstraintLayout>

![image](https://github.com/user-attachments/assets/f2513f6a-63fb-4961-890a-2e9b098eaa48)

'''

''' login.xml 
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">


    <ImageView
        android:id="@+id/loginnscreen"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_marginEnd="4dp"
        android:scaleType="centerCrop"
        android:src="@drawable/login"
        app:layout_constraintEnd_toEndOf="parent"
        tools:layout_editor_absoluteY="0dp" />

    <Button
        android:id="@+id/login"
        android:layout_width="277dp"
        android:layout_height="98dp"
        android:backgroundTint="#F44336"
        android:text="Login"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.253"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/loginnscreen"
        app:layout_constraintVertical_bias="0.739"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@+id/username"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="266dp"
        android:layout_marginBottom="420dp"
        android:ems="10"
        android:inputType="text"
        android:text="Name"
        app:layout_constraintBottom_toBottomOf="@+id/loginnscreen"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/loginnscreen"
        tools:ignore="MissingConstraints,TouchTargetSizeCheck" />

    <EditText
        android:id="@+id/Password"
        android:layout_width="270dp"
        android:layout_height="42dp"
        android:layout_marginTop="344dp"
        android:ems="10"
        android:inputType="text"
        android:text="Password"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/loginnscreen"
        app:layout_constraintHorizontal_bias="0.51"
        app:layout_constraintStart_toStartOf="@+id/loginnscreen"
        app:layout_constraintTop_toTopOf="@+id/loginnscreen"
        app:layout_constraintVertical_bias="0.092"
        tools:ignore="MissingConstraints,TouchTargetSizeCheck" />


</androidx.constraintlayout.widget.ConstraintLayout>
'''

''' activityregister.xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">


    <ImageView
        android:id="@+id/loginnscreen"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_marginEnd="4dp"
        android:scaleType="centerCrop"
        android:src="@drawable/login"
        app:layout_constraintEnd_toEndOf="parent"
        tools:layout_editor_absoluteY="0dp" />

    <Button
        android:id="@+id/login"
        android:layout_width="277dp"
        android:layout_height="98dp"
        android:backgroundTint="#F44336"
        android:text="Login"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.253"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/loginnscreen"
        app:layout_constraintVertical_bias="0.739"
        tools:ignore="MissingConstraints" />

    <EditText
        android:id="@+id/username"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="266dp"
        android:layout_marginBottom="420dp"
        android:ems="10"
        android:inputType="text"
        android:text="Name"
        app:layout_constraintBottom_toBottomOf="@+id/loginnscreen"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/loginnscreen"
        tools:ignore="MissingConstraints,TouchTargetSizeCheck" />

    <EditText
        android:id="@+id/Password"
        android:layout_width="270dp"
        android:layout_height="42dp"
        android:layout_marginTop="344dp"
        android:ems="10"
        android:inputType="text"
        android:text="Password"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/loginnscreen"
        app:layout_constraintHorizontal_bias="0.51"
        app:layout_constraintStart_toStartOf="@+id/loginnscreen"
        app:layout_constraintTop_toTopOf="@+id/loginnscreen"
        app:layout_constraintVertical_bias="0.092"
        tools:ignore="MissingConstraints,TouchTargetSizeCheck" />


</androidx.constraintlayout.widget.ConstraintLayout>
'''
''' gallery.xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <ImageView
        android:id="@+id/galleryscreen"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        android:src="@drawable/gallery"
        app:layout_constraintEnd_toEndOf="parent"/>
        tools:layout_editor_absoluteY="0dp"/>

</androidx.constraintlayout.widget.ConstraintLayout>
'''

''' Androidmanifestxml
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <application
        android:allowBackup="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.PinterestApp"
        tools:targetApi="31">
        <activity
            android:name=".splash_screen"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>


    <activity
        android:name=".login_screen"
        android:exported="true" />

        <activity
            android:name=".register_screen"
            android:exported="true" />

        <activity
            android:name=".galery_screen"
            android:exported="true" />

</application>
</manifest>

'''

'''splashscreen.kt
package com.example.pinterestapp

import android.content.Intent
import android.os.Bundle
import android.os.Handler
import android.os.Looper
import androidx.appcompat.app.AppCompatActivity

class splash_screen : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.splashscreenactivity) // pastikan ini adalah XML splash

        // Delay 3 detik, lalu pindah ke Login
        Handler(Looper.getMainLooper()).postDelayed({
            val intent = Intent(this, login_screen::class.java)
            startActivity(intent)
            finish() // tutup Splash agar tidak bisa kembali
        }, 3000)
    }
}


loginscreen.kt
package com.example.pinterestapp

import android.content.Intent
import android.os.Bundle
import android.widget.Button
import androidx.appcompat.app.AppCompatActivity

class login_screen : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.login) // Memanggil layout login.xml

        // Temukan tombol login berdasarkan ID
        val loginButton: Button = findViewById(R.id.login)

        // Saat tombol diklik, pindah ke RegisterScreen
        loginButton.setOnClickListener {
            val intent = Intent(this, register_screen::class.java)
            startActivity(intent)
            finish()
        }
    }
}


registerscreen.kt

package com.example.pinterestapp

import android.content.Intent
import android.os.Bundle
import android.widget.Button
import androidx.appcompat.app.AppCompatActivity

class register_screen : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activityregister) // ini memanggil login.xml
        // Temukan tombol login berdasarkan ID
        val loginButton: Button = findViewById(R.id.submit)

        // Saat tombol diklik, pindah ke RegisterScreen
        loginButton.setOnClickListener {
            val intent = Intent(this, galery_screen::class.java)
            startActivity(intent)
            finish()
        }
    }
}

galeryscreen.kt

package com.example.pinterestapp

import android.os.Bundle
import androidx.appcompat.app.AppCompatActivity

class galery_screen : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.gallery) // ini memanggil login.xml
    }
}


'''
