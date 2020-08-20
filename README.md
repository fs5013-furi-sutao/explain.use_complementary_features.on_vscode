# VSCode の補完機能を使ってコーディングをスピードアップしよう
VSCode には自動補完機能がある。

補完機能とは、入力された文字列から推測して、ユーザの入力を補助してくれる機能のことだ。

以下の例を見てみよう。

## 今回のサンプルコード
例えば、次のような簡単なコードを例にとって、補完機能を使ってみる。

```java
public class App {

    public static void main(String[] args) {
        System.out.println("Hello world.");
    }
}
```

## 補完機能を利用するコーディング手順
補完を効かせながらコーディングする流れは次の通り。

1. `class` と入力
2. 候補に `class` と `class template` がリストアップ表示される
3. `class template` を選択
4. Enter で決定

```java
/**
 * App
 */
public class App {

    
}
```

5. `main` と入力
6. 候補のトップに `main template` がリストアップ表示される
7. `main template` を選択
8. Enter で決定

```java
/**
 * App
 */
public class App {

    public static void main(String[] args) {
        
    }
}
```

9. `sysout` と入力
10. 候補に `sysout template` のみがリストアップ表示される
11. Enter で決定

```java
/**
 * App
 */
public class App {

    public static void main(String[] args) {
        System.out.println("Hello world.");
    }
}
```

12. `"Hello world."` を入力
13. ファンクションキー `F5` を押す
14. プログラムの実行結果が表示される

![VSCode 自動補完機能の使用例](./coding_and_running.gif)

スピードアップを意識して、どんどんコーディングをファンキーにしていこう～

