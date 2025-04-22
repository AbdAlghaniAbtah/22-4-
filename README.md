void main() {
  List<String> favoriteColors = ["red", "green", "blue"]; 
  for (int i = 0; i < favoriteColors.length; i++) print(favoriteColors[i]);
  Map<String, dynamic> meal = {
    "name": "Pizza ",
    "calories": 280,
    "isHealthy": false,
  };
  if (meal["isHealthy"] == true) 
    print("This is a healthy meal ");
  else 
    print("This is not a healthy meal" );
  
  String firstColor = favoriteColors[0]; 
  switch (firstColor) {
    case "green":
      print("The best color is green ");
    case "red":
      print("The best color is green ");
    case "blue":
      print("The best color is green ");
  }
}
