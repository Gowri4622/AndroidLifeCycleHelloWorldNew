# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “ex.no.1″ and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by: Gowri M
Registeration Number : 212220230019
*/
```
### MainActivity.java
```java
package com.example.exno1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",
        Toast.LENGTH_LONG);
        toast.show();
    }
}
```

### activity_main.xml
```java
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.
android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
## OUTPUT
![WhatsApp Image 2022-04-26 at 9 21 51 PM (2)](https://user-images.githubusercontent.com/75235455/168122477-135e6575-e705-434e-ac56-f1b5400a68c8.jpeg)
![WhatsApp Image 2022-04-26 at 9 21 51 PM (3)](https://user-images.githubusercontent.com/75235455/168122466-fe358a7f-5d44-482e-aa59-15739d88702f.jpeg)
![WhatsApp Image 2022-04-26 at 9 21 51 PM (1)](https://user-images.githubusercontent.com/75235455/168122482-974878e9-0ee8-434c-b44a-e9967ee1cc89.jpeg)
![WhatsApp Image 2022-04-26 at 9 21 51 PM](https://user-images.githubusercontent.com/75235455/168122486-820a4b0c-d9ee-42d7-ad18-884ec40297cf.jpeg)
![WhatsApp Image 2022-04-26 at 9 23 55 PM](https://user-images.githubusercontent.com/75235455/168122487-289aa6de-555c-4c46-9d06-5d57e7a36078.jpeg)
![WhatsApp Image 2022-04-26 at 9 23 38 PM](https://user-images.githubusercontent.com/75235455/168122492-df35b912-16e0-4b60-8b98-6074730abc96.jpeg)
![WhatsApp Image 2022-04-26 at 9 21 51 PM (4)](https://user-images.githubusercontent.com/75235455/168122495-a3098468-d962-4c30-950d-eb85ebe36b90.jpeg)




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
