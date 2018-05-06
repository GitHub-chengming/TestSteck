# TestSteck
打印一周天数，剩余天数
public static void main(String[] args){
  int days=46;
  int week=days/7;
  System.out.println("总共周数:"+week);
  int leftDay=days%7;
  System.out.println("剩余的天数:"+leftDay);
}
