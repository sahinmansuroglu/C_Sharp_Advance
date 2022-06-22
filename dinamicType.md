public class Program
{
	public static void Main()
	{
		dynamic stud = new Student();
		stud.DisplayStudentInfo(1, "Bill");
		stud.DisplayStudentInfo("1");
		stud.FakeMethod();
	}
}

public class Student
{
	public void DisplayStudentInfo(int id)
	{
		Console.WriteLine("Dummy Student");
	}
}

http://letsgotocoding.blogspot.com/2018/02/cta-dynamic-tipler.html
