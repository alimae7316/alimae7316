// Example login button event
private void btnLogin_Click(object sender, EventArgs e) {
    string username = txtUsername.Text;
    string password = txtPassword.Text;
    // Validate credentials (add your logic)
    if (username == "admin" && password == "password") {
        // Open main form
        MainForm mainForm = new MainForm();
        mainForm.Show();
        this.Hide();
    } else {
        MessageBox.Show("Invalid credentials.");
    }
}
