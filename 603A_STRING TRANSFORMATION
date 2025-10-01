import java.util.Scanner;

public class CharacterCounter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();  // Read input string
        scanner.close();

        // Counters
        int vowels = 0, consonants = 0, digits = 0, specialChars = 0;

        // Convert to lowercase for easy vowel checking
        input = input.toLowerCase();

        for (char ch : input.toCharArray()) {
            if ("aeiou".indexOf(ch) != -1) {       // Check vowels
                vowels++;
            } else if (Character.isLetter(ch)) {   // Check consonants
                consonants++;
            } else if (Character.isDigit(ch)) {    // Check digits
                digits++;
            } else {                               // Everything else → special chars
                specialChars++;
            }
        }

        // Output
        System.out.println("Vowels: " + vowels);
        System.out.println("Consonants: " + consonants);
        System.out.println("Digits: " + digits);
        System.out.println("Special Characters: " + specialChars);
    }
}
