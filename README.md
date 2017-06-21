# HW-VoidFunctions
Watch read and practice from the module: Functions. Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

The first 3 examples are based on the Unity tutorials.

1.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		print(myInt);
	}

}

2.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		print(myInt * 4);
	}

}

3.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		myInt = 25;
		print(myInt * 4);
	}

}

The next four are examples based on Preston's lesson in class today.

4.

public class VoidFunctions : MonoBehaviour {

  public int num1;
  public int num2;

  void Start()
  {
    int num = AddNumbers(num1, num2);
    print(num);
  }

  public int AddNumbers(int number1, int number2)
  {
    int result = number1 + number2;

    return result;
  }

}

5.

 public int num1;
  public int num2;

  void Update()
  {
    int num = AddNumbers(num1, num2);
    print(num);
  }

  public int AddNumbers(int number1, int number2)
  {
    int result = number1 + number2;

    return result;
  }

6.

public class VoidFunctions : MonoBehaviour
{

  public static int AddNumbers(int number1, number2)
  {
    int result = number1 + number2;
    
    return result;
  }
  
  int num = AddNumbers(10, 2);

}

7.

public class Toaster : MonoBehaviour {

	public int slot1;
	public int slot2;

	void Start()
	{

		if(slot1 == 1 || slot2 == 1)
		{
			print("Bread is toasted!");
		}
		else
		{
			print("Nothing is toasted!");
		}

	}

}

8.

public class VoidFunctions : MonoBehaviour {

	public int PlayerAttack;
	public int EnemyDefense;

	void Start()
	{
		int num = SubtractNumbers(PlayerAttack, EnemyDefense);
		print(num);
	}

	public int SubtractNumbers(int PlayerAttack, int EnemyDefense)
	{
		int result = PlayerAttack - EnemyDefense;
		return result;
	}

}

9. 

