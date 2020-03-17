# Main6_1
//メインクラス　6-1
public class Maindai6_1{
  public static void main(String[] args) throws Exception {
    String doWarusa = comment.Zenhan.doWarusa();
    String doTogame = comment.Zenhan.doTogame();
    String callDeae = comment.Kouhan.callDeae();
    String showMondokoro = comment.Kouhan.showMondokoro();
    System.out.println(doWarusa + "\n" +doTogame + "\n" + callDeae + "\n" + showMondokoro );

    System.out.println(comment.Zenhan.doTogame());//もういちどとがめる
  }
}
