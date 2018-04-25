package JustTest;

import java.util.Date;

public class test1 {

	static{
		System.out.println("我是初始化动作，我比main方法级别都高，先执行我一次哦");
	}

	public static void main(String[] args) {
		
		Date date = new Date();
		String a = String.format("%tY", date);
		String a = String.format("%tY","%tb","%te","%tA", date);
		System.out.println(date);
		System.out.println(a);
		
		
		StringBuilder s = new StringBuilder("asdf,adfg,uy,hk,awet,3456,set,wert,357u,wte34");
		System.out.println(s.length());
		s.append("***");
		s.insert(0, "---");
		s.insert(25, "+++");
		System.out.println(s);
		
/*		for (int i = 0; i < 5; i++) {
			
			for (int j = 0; j < i; j++) {
				System.out.print("*");
			}
			System.out.println(i);
		}
*/		

		
	}
}
