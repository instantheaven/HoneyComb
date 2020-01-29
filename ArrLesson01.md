# 配列について
** 自分用のメモ書き**
---

```java
public class ArrayLesson01{
	public static void main(String[] args){
		int[] nums;//配列の宣言
		int[] nums=new int[3];//配列の要素数を３つにする
		int[] nums={10.20.30};//配列の要素に10,20,30の値を入れる
		for(int i=0;i<nums.length;i++){
			nums[i]=i;//iの値を配列に格納する(0,1,2)
			nums[i]=i+1;//iの値に+1したものを配列に格納する(1,2,3)
		}
		int a=nums[0];//配列の一番最初
		int a=nums[nums.length-1];//配列の一番最後(インデックスは要素数より1少ないため)
		System.out.println(nums[]);//数字が入ってないのでエラー
		System.out.println(nums[nums.length]);//この要素数はないためエラー
		System.out.println(nums.length);//要素数を表示

		int data=0;
		nums[data];//dataはインデックスの数字
		nums[]=data;//dataは要素に入るからこのままだとエラー
		nums[0]=data;//インデックスを指定すればOK
	}
}
```
