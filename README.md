namespace OPERACION_GIF_
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void pictureBox1_Click(object sender, EventArgs e)
        {
            pictureBox1.Image = Image.FromFile("C:\\Users\\DELTA\\Documents\\proyecto gif\\giphy.gif");
            pictureBox1.SizeMode = PictureBoxSizeMode.StretchImage;
        }

        private void pictureBox1_Click_1(object sender, EventArgs e)
        {
        
        }
    }
}
