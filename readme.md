## Assignment:

Create a GitHub Actions workflow that will trigger on every push to the **`main`** branch of your repository. The workflow should do the following:

1. Create a file named **`message.txt`** and add a message to it.
2. Print the current working directory.
3. Print the contents of the **`message.txt`** file.
4. Use the **`echo`** command to print a custom message.

**Requirements:**

1. The workflow must be defined in a YAML file and stored in the **`.github/workflows`** directory of the repository.
2. The workflow should trigger on every push to the **`main`** branch of the repository.
3. The workflow should have at least four jobs:
   - A job to create the **`message.txt`** file.
   - A job to print the current working directory.
   - A job to print the contents of the **`message.txt`** file.
   - A job to print a custom message using the **`echo`** command.
4. Create a scheduled version of the same workflow running every midnight and every Friday midnight. (You can give any schedule for testing purpose.)

**Note:**

You can customize the message in the **`message.txt`** file and the custom message printed using the **`echo`** command.
