import javax.swing.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class Main {
    private JFrame frame;
    private JPasswordField passwordField;
    private JButton enterButton;
    private JButton clearButton;
    private JLabel statusLabel;
    private String savedPassword = null;

    public Main() {
        frame = new JFrame("Locker Application");
        frame.setSize(300, 350);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setLayout(null);

        // Add number buttons
        JPanel buttonPanel = new JPanel();
        buttonPanel.setBounds(50, 20, 200, 100);
        buttonPanel.setLayout(new java.awt.GridLayout(3, 3, 5, 5));

        for (int i = 1; i <= 9; i++) {
            JButton button = new JButton(String.valueOf(i));
            button.addActionListener(new ActionListener() {
                @Override
                public void actionPerformed(ActionEvent e) {
                    passwordField.setText(passwordField.getText() + button.getText());
                }
            });
            buttonPanel.add(button);
        }

        frame.add(buttonPanel);

        JLabel passwordLabel = new JLabel("Enter Passcode:");
        passwordLabel.setBounds(10, 150, 120, 25);
        frame.add(passwordLabel);

        passwordField = new JPasswordField();
        passwordField.setBounds(140, 150, 120, 25);
        frame.add(passwordField);

        enterButton = new JButton("Enter");
        enterButton.setBounds(50, 190, 80, 25);
        frame.add(enterButton);

        clearButton = new JButton("Clear");
        clearButton.setBounds(150, 190, 80, 25);
        frame.add(clearButton);

        statusLabel = new JLabel();
        statusLabel.setBounds(10, 230, 250, 25);
        frame.add(statusLabel);

        enterButton.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
                handleEnterButton();
            }
        });

        clearButton.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
                passwordField.setText("");
            }
        });

        frame.setVisible(true);
    }

    private void handleEnterButton() {
        String enteredPassword = new String(passwordField.getPassword());

        if (savedPassword == null) {
            // Setting the password for the first time
            savedPassword = enteredPassword;
            statusLabel.setText("Password Set");
        } else {
            // Verifying the password
            if (savedPassword.equals(enteredPassword)) {
                statusLabel.setText("Correct Password");
            } else {
                statusLabel.setText("Incorrect Password");
            }
        }

        // Clear the password field
        passwordField.setText("");
    }

    public static void main(String[] args) {
        SwingUtilities.invokeLater(new Runnable() {
            @Override
            public void run() {
                new Main();
            }
        });
    }
}
