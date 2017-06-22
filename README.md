# HW-VoidFunctions
Watch read and practice from the module: Functions. Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

The first 3 examples are based on the Unity tutorials.

1. myInt is assigned to 3; and within the scope of the Void Function, myInt can be printed to the Unity Console window. Pretty simple...

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		print(myInt);
	}

}

2. To expand from the previous example, before myInt can get printed, this example shows that it get's multiplied by 4, so it prints "12".

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		print(myInt * 4);
	}

}

3. Now in this example, this shows that a new myInt (within the scope of the VF) has been assigned to 25, which now overrides the myInt outside of the void. So now with that, and while it multiplies by 4; its actually printing "100".

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		myInt = 25;
		print(myInt * 4);
	}

}

The next four (4 - 7) are examples based on Preston's lesson in class today.

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

public class VoidFunctions : MonoBehaviour {

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

public class VoidFunctions : MonoBehaviour {

	public int player1cards = 5;
	public int player2cards = 5;

	void Start()
	{
		if(player1cards == 5 && player2cards == 5)
		{
			print("Now we can play GoFish.");
		}
		else
		{
			print("Player 1 &/or 2 still needs more card(s).");
		}
	}
}

10.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		myInt = 9;
		print(myInt / 3);
	}

}
