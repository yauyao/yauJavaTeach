# 如何在程式中印出圖形

## 方形
首先，先利用最簡單的方式印出6*6方形陣列
```
public class Square{
    public static void main(String[] arg){
        System.out.println("******");
        System.out.println("******");
        System.out.println("******");
        System.out.println("******");
        System.out.println("******");
        System.out.println("******");
    }
}
```
印出結果如下:
```
******
******
******
******
******
******
```
邏輯分析:
|字詞|說明|
|---|---|
|public|為公開、公用，其它封包皆可以讀取並使用|
|class|用於定義這個有一個叫Square的類別，可以讓別人呼叫使用|
|static|定義為靜態方法,在程式載入記憶體的時候，跟著程式一起在記憶體中佔有空間，而不是主程式開始執行後才跟記憶體要空間. |
|void|該方法不具有回傳值|
|System.out.println|印出小刮弧內的字串並進行換行|

