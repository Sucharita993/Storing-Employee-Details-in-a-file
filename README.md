# Storing-Employee-Details-in-a-file
We generally store data into a text either by using printwriter or BufferWriter, etc.
In our code, we have used printWriter<br>
PrintWriter throws "FileNotFound Exception"<br>
In order to over this we wrote the whole process in try catch block.<br>
```java
	try {
} catch (Exception e) {
			System.out.println(e);
		}
    ```
As we usually write, this code is used for storing the employee record into the text file<br>
```javaPrintWriter pw = new PrintWriter(new FileOutputStream(file, true));

			BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
 ```
 
