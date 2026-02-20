package com.example.mywebapp;

import android.os.Bundle;
import android.widget.TextView;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);

        // Ek simple text view bana raha hoon
        TextView textView = new TextView(this);
        textView.setText("Hello! Yeh mera pehla Android Code hai.");
        textView.setTextSize(24);
        
        setContentView(textView);
    }
}
