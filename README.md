# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by:Swetha.S
Registeration Number :212221040169
*/
```
```
MainActivity.java:-

package com.example.My Application;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle; import android.widget.Toast;
public class MainActivity extends AppCompatActivity {

@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Toast t = Toast.makeText(getApplicationContext(),"onCreate Called",Toast.LENGTH_LONG);
    t.show();
}

protected void onStart(){
    super.onStart();
    Toast t = Toast.makeText(getApplicationContext(),"onStart Called",Toast.LENGTH_LONG);
    t.show();
}

protected void onRestart(){
    super.onRestart();
    Toast t = Toast.makeText(getApplicationContext(),"onRestart Called",Toast.LENGTH_LONG);
    t.show();
}

protected void onPause(){
    super.onPause();
    Toast t = Toast.makeText(getApplicationContext(),"onPause Called",Toast.LENGTH_LONG);
    t.show();
}

protected void onResume(){
    super.onResume();
    Toast t = Toast.makeText(getApplicationContext(),"onResume Called",Toast.LENGTH_LONG);
    t.show();
}

protected void onStop(){
    super.onStop();
    Toast t = Toast.makeText(getApplicationContext(),"onStop Called",Toast.LENGTH_LONG);
    t.show();
}

protected void onDestroy(){
    super.onDestroy();
    Toast t = Toast.makeText(getApplicationContext(),"onDestroy Called",Toast.LENGTH_LONG);
    t.show();
}
}
```
```
Activity_main.xml:-
<androidx.constraintlayout.widget.ConstraintLayout 
xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto" 
xmlns:tools="http://schemas.android.com/tools" 
android:layout_width="match_parent" 
android:layout_height="match_parent" 
tools:context=".MainActivity">

<TextView
    android:id="@+id/head"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:fontFamily="@font/arbutus_slab"
    android:text="Mobile Application Development"
    android:textColor="@color/Maroon"
    android:textSize="20sp"
    app:layout_constraintBottom_toTopOf="@+id/body"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent" />

<TextView
    android:id="@+id/body"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_marginBottom="356dp"
    android:fontFamily="@font/expletus_sans_medium"
    android:text="HELLO WORLD"
    android:textColor="@color/MediumTurquoise"
    android:textSize="20sp"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.498"
    app:layout_constraintStart_toStartOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```

## OUTPUT

![1](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/0d443a0a-17f4-43ef-90da-3256daf46692)
![start](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/33c4870c-c1dd-449d-ba3b-f802e77f60c5)
![2](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/2fe8241a-9aff-444d-9055-0e66b6c27cbc)
![3](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/5516a249-79a4-45c0-9888-90d34b78a034)
![4](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/69f80e0e-ce50-498b-93e3-7f4661353b7c)
![5](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/18f84813-ff6f-4f77-8784-5a25126980e4)
![6](https://github.com/SWETHA6302/Mobile-Application-Development/assets/127874947/f31f0ce1-50c4-4c27-8623-fa51c525f623)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
