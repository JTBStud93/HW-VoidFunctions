# HW-VoidFunctions
Watch read and practice from the module: Functions. Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

Examples from class

1. 

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

2.

public class VoidFunctions : MonoBehaviour
{

  public static int AddNumbers(int number1, number2)
  {
    int result = number1 + number2;
    
    return result;
  }
  
  int num = AddNumbers(10, 2);

}

3.

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

A few examples based on the Unity tutorials

4.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		print(myInt);
	}

}

5.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		print(myInt * 4);
	}

}

6.

public class VoidFunctions : MonoBehaviour {

	int myInt = 3;

	void Start()
	{
		myInt = 25;
		print(myInt * 4);
	}

}
