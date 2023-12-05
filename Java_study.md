# Java  

## Javaプログラム作成から実行までの手順  
- ファイルの作成  
  ・テキストエディタで新しいファイルを作成し、拡張子を.javaとして保存
- Javaファイルを開き、Javaプログラムを記述  
  ・1行目のpublic classの後はクラス名を記述する。Javaのルールとしてファイル名は「クラス名.java」にしなければならない  
  ・2行目のpublic static void main(String[] args)は特に正確な記述が求められる  
  ・3行目のSystem.out.println()の()内に入力した記述が出力される
  ・()に入力するのが文字の時は""で挟む、数字の時は不要
  ・コード例  
    public class MyProgram {
      public static void main(String[] args) {
        System.out.println("Hello, World!");
      }
    }  
- コンパイル  
  ・ターミナルまたはコマンドプロンプトを開き、Javaファイルが保存されているディレクトリに移動する  
　・javacコマンド(javac クラス名.java)を使用してJavaファイルをコンパイルする  
- 実行  
  ・コンパイルが成功したら、javaコマンド(java クラス名)を使用してプログラムを実行する  
