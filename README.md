# WebView-api
 WebView webView = (WebView) findViewById(R.id.webView);
        webView.getSettings().setJavaScriptEnabled(true);
        webView.setWebViewClient(new WebViewClient());
        webView.loadUrl("http://www.google.com");

        //TO LOAD EXTERNAL DATA

        webView.loadData("<html><body><h1>HI THERE!</h1></body></html>" , "text/html" , "UTF-8");
