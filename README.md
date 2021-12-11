int x = 0; 
int y = 30; 
private void timer1_Tick(object sender, System.EventArgs e)
{
// label1.Text = label1.Text.Substring(1) + label1.Text.Substring(0,1); 
label1.Location = new Point(x, label1.Location.Y); 
label2.Location = new Point(label1.Location.Y, y); 
x -= 5; 
y += 5; 
if (x < 0) x = 425; 
if (y > 260) y = 30; 
}
