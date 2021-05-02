# Windows2019RDP-AP

Windows Server 2019 Github with RDP Access (ngrok AP)

Create a free VPS with 2cpu-7gb Ram FREE configuration with Github:

- Click Fork in the right corner of the screen to save it to your Github.
- Visit https://dashboard.ngrok.com to get NGROK_AUTH_TOKEN

In Github go to Settings> Secrets> New repository secret
* Name: enter NGROK_AUTH_TOKEN
*Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken and then 
press add secret
Go to Action> CI2> Run workflow
Reload the page and press CI2> build
Press the down arrow on Connect To Your RPD to get IP, User, Password.
#### Cre: https://github.com/ThuongHai
