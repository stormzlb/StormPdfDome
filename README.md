# 依赖该库   

# 具体使用:
           Intent intent = new Intent(xxxx.this, DocumentActivity.class);
                intent.addFlags(Intent.FLAG_ACTIVITY_CLEAR_WHEN_TASK_RESET);
                intent.setAction(Intent.ACTION_VIEW);
                intent.setData(Uri.fromFile(new File("/mnt/sdcard/abc.pdf")));
                startActivity(intent);
