package edu.cqut.MobileOrderFood;
import android.os.Bundle;
import andriod .app.Activity;
import android.view.Menu;

public class MainActivity extends Activity{
@Override
public boolean onCreate(Bundle saveInstanceState){
super.onCreate(savedInstanceState);
setContentView(R.layout.activity_main);
}
@Override
public boolean onCreateOptionsMenu(Menu menu){
//Inflate the menu;this adds items to the action bar if it is present.
getMenuInflater().inflate(R.menu.main,menu);
return true;
}
}

