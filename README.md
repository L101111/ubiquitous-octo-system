<h1>Automatically Update the System</h1>
<p>This is a simple bash script that will automatically update your system. For the script to actually work you have to add some configurations to your crontab.</p>
<h3>To do that:</h3>
  
      $ sudo crontab -e

<img src='https://github.com/L101111/ubiquitous-octo-system/blob/main/screen.png' width='600px' />
      
      $ 00 00 * * * /path/to/upd.sh
      
<p>Now your system will automatically get updated every day at 12AM.</p>

# Enjoy
