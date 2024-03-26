void main() {
  // Integers
  int age = 22; // Represents whole numbers
  print('Age: $age');

  // Doubles
  double weight = 54.5; // Represents decimal numbers
  print('Weight: $weight');

  // Strings
  String name = 'Nadine Mugweru'; // Represents text
  print('Name: $name');

  // Lists
  List<String> friends = ['Jane', 'Sandra', 'John']; // Represents a collection of elements
  print('Friends: $friends');

  // Maps
  Map<String, dynamic> person = {
    'name': 'Nadine',
    'age': 22,
    'isStudent': true,
  }; // Represents key-value pairs
  print('Person: $person');

  // Testing access and modification of elements in List and Map
  print('First friend: ${friends[0]}'); // Accessing the first friend in the list
  person['age'] = 22; // Modifying age in the map
  print('Updated person: $person');
}
