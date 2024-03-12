import java.util.Scanner;

public class GestureRecognitionSystem {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to perform a gesture
        System.out.println("Please perform a gesture (e.g., wave hand, make a fist):");
        String gesture = scanner.nextLine();

        // Recognize the gesture
        String action = recognizeGesture(gesture);

        // Output the recognized action
        System.out.println("Recognized action: " + action);

        scanner.close();
    }

    // Method to recognize the gesture and return the corresponding action
    public static String recognizeGesture(String gesture) {
        // Simple gesture recognition logic
        if (gesture.contains("wave")) {
            return "Wave detected. Opening door.";
        } else if (gesture.contains("fist")) {
            return "Fist detected. Turning off lights.";
        } else {
            return "Unrecognized gesture. No action taken.";
        }
    }
}
