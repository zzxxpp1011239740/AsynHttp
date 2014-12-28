package com.james.asynhttp;

import android.app.Activity;
import android.os.Bundle;
import android.util.Log;
import android.view.Menu;
import android.view.MenuItem;

/**
 *  各种案例
 * @author james
 *
 */
public class MainActivity extends Activity {

	@Override
	protected void onCreate(Bundle savedInstanceState) {
		super.onCreate(savedInstanceState);
		setContentView(R.layout.activity_main);
		//  get request simple demo
		new AsynHttpClient().get("http://news.baidu.com/", new HttpNetWorkDataHandler() {
			
			@Override
			public void success(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				Log.e("tag----", obj.toString());
			}
			
			@Override
			public void failure(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
		});
		
		//post request simple demo
		new AsynHttpClient().post("http://news.baidu.com", "{content : ['':'']}", new HttpNetWorkDataHandler() {
			
			@Override
			public void success(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
			
			@Override
			public void failure(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
		});
		
		
		// download requset simple demo
		new AsynHttpClient().download("http://file/download/nhb.apk", new HttpNetWorkDataHandler() {
			
			@Override
			public void success(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
			
			@Override
			public void failure(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
		});
		
		//download requset simple demo
		new AsynHttpClient().downloadBitMap("http://file/download/nhb.jpg", new HttpNetWorkDataHandler() {
			
			@Override
			public void success(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
			
			@Override
			public void failure(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
		});
		
		// upload requset simple demo 
		new AsynHttpClient().upload("http://file/upload", "/sdcard/nhb/sss.jpg", new HttpNetWorkDataHandler() {
			
			@Override
			public void success(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
			
			@Override
			public void failure(int statusCode, Object obj) {
				// TODO Auto-generated method stub
				
			}
		});
		
	}
}
