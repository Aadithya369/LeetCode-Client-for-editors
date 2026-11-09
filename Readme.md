The project currently has the required core features working properly. 
Avaliable features (hope you can understand this)
   ```java 
switch (args[0]) {
      case "1":
        response = client.getProblemList();
        break;
      case "2":
        response = client.getQuestionOfToday();
        break;
      case "3":
        response = client.getProblem(args[1]);
        break;
      case "4":
        response = client.getNextQuesiton(args[1]);
        break;
      case "5":
        response = client.getPrevQuesiton(args[1]);
        break;
      case "6":
        response = client.getSolvedProblemList();
        break;
      case "7":
        response = client.getRandomQuestion();
        break;
      case "8":
        response = client.getFavoriteList(args[1]);
        break;
      case "9":
        response = client.submitCode(args[1], args[2], args[3], args[4]);
        break;
      case "10":
        response = client.getCodeSnippets(args[1], args[2]);
        break;
      case "11":
        response = client.getExampleTestCases(args[1]);
        break;
      case "12":
        response = client.getListOfLanguages(args[1]);
        break;
      default:
        response = "wrong argument";
```
Set the `$LEETCODE_COOKIE` and `$LEETCODE_CSRF` to valid tokens obtained from a valid leetcode session.
