# Ex.No: 2 To develop an application that uses GUI Components with Fonts and Colors. 
Note: Create button for colors and fonts while clicking color or font button should change 


## AIM:

To create an application that uses GUI Components with Fonts and Colors using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:


## PROGRAM:
```
/*
Program to print the text “GUIcomponent”.
Developed by:S.MONICKA
Registeration Number :212221220033
*/
```
##Activitymain.xml
```
<?xml version="1.0" encoding="utf-8"?> 
<androidx.constraintlayout.widget.ConstraintLayout 
xmlns:android="http://schemas.android.com/apk/res/android" 
    xmlns:app="http://schemas.android.com/apk/res-auto" 
    xmlns:tools="http://schemas.android.com/tools" 
    android:layout_width="match_parent" 
    android:layout_height="match_parent" 
    tools:context=".MainActivity"> 
 
    <TextView 
        android:id="@+id/textView" 
        android:layout_width="339dp" 
        android:layout_height="124dp" 
        android:text="GOOGLE" 
        android:fontFamily="cursive" 
        android:textAlignment="center" 
        android:textSize="80sp" 
        app:layout_constraintBottom_toBottomOf="parent" 
        app:layout_constraintEnd_toEndOf="parent" 
        app:layout_constraintStart_toStartOf="parent" 
        app:layout_constraintTop_toTopOf="parent" 
        app:layout_constraintVertical_bias="0.36" />
 <Button 
        android:id="@+id/button" 
        android:layout_width="120dp" 
        android:layout_height="120dp" 
        android:text="COLOUR" 
        app:layout_constraintBottom_toBottomOf="parent" 
        app:layout_constraintEnd_toStartOf="@+id/button2" 
        app:layout_constraintHorizontal_bias="0.515" 
        app:layout_constraintStart_toStartOf="parent" 
        app:layout_constraintTop_toTopOf="parent" 
        app:layout_constraintVertical_bias="0.706" />
<Button 
        android:id="@+id/button2" 
        android:layout_width="120dp" 
        android:layout_height="120dp" 
        android:layout_marginEnd="56dp" 
        android:text="FONT" 
        app:layout_constraintBottom_toBottomOf="parent" 
        app:layout_constraintEnd_toEndOf="parent" 
        app:layout_constraintTop_toTopOf="parent" 
        app:layout_constraintVertical_bias="0.706" /> 
</androidx.constraintlayout.widget.ConstraintLayout>
```

## OUTPUT




## RESULT
Thus a Simple Android Application that uses GUI Components with Fonts and Colors using Android Studio is developed and executed successfully.


