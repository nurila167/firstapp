# firstapp
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:gravity="center"
        android:text = " English (United States)▼ "
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="250dp"
        android:layout_height="190dp"
        android:layout_marginTop="96dp"
        android:src="@drawable/instagram_logo"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />

    <EditText
        android:id="@+id/account"
        android:layout_width="380dp"
        android:layout_height="wrap_content"
        android:background="@drawable/edittext"
        android:hint="Phone number, email or username"
        android:padding="12dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView"
        app:layout_constraintEnd_toEndOf="parent"/>

    <EditText
        android:id="@+id/passwordField"
        android:layout_width="380dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="4dp"
        android:background="@drawable/edittext"
        android:hint="Password"
        android:drawableEnd="@drawable/baseline_remove_red_eye_24"

        android:padding="12dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/account" />

    <Button
        android:id="@+id/button"
        android:layout_width="380dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:backgroundTint="#3897F0"
        android:padding="16dp"
        android:text="Log in"
        android:textAllCaps="false"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/passwordField" />

    <TextView
        android:id="@+id/textForgot"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="522dp"
        android:text="Forgot your login details?"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.225"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textView" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="522dp"
        android:text="  Get help loggin in."
        android:textColor="#333333"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.743"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textView" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="560dp"
        android:text="OR"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <ImageView
        android:layout_width="38dp"
        android:layout_height="48dp"
        android:layout_marginTop="588dp"
        android:src="@drawable/facebook_logo"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.265"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:layout_width="142dp"
        android:layout_height="27dp"
        android:layout_marginStart="4dp"
        android:layout_marginTop="80dp"
        android:backgroundTint="#3897F0"
        android:text="Log in with Facebook"
        android:textColor="#3897F0"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textForgot" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="48dp"
        android:layout_marginTop="705dp"
        android:text="Don't have an account?"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.397"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="48dp"
        android:layout_marginTop="705dp"
        android:text=" Sign up."
        android:textColor="#333333"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.701"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <View
        android:layout_width="190dp"
        android:layout_height="3dp"
        android:background="@drawable/edittext"
        android:layout_marginTop="568dp"
        android:layout_marginStart="-220dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"/>

    <View
        android:layout_width="190dp"
        android:layout_height="3dp"
        android:layout_marginStart="-220dp"
        android:layout_marginTop="568dp"
        android:background="@drawable/edittext"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />


</androidx.constraintlayout.widget.ConstraintLayout>
