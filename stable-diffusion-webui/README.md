Sign up for a Kaggle account by visiting [kaggle](https://www.kaggle.com/) Make sure to verify your email and phone number(you get 30hr free tesla T4 gpu for free :))

Register for a Ngrok account at[Ngrok](https://ngrok.com/) and copy your AUTH token.

Create a new notebook.
Change the accelerator to a GPU T4 for better performance.

Clone the repository:

```bash
git clone https://github.com/shashankmcode/Stable-Diffusion-on-kaggle
```
change the directory to stable-diffusion-webui

Excecute the following. You can pass additional COMMANDLINE_ARGS as needed
```bash
ngrok_token = "NGROK_TOKEN" ARGS = f"--ngrok {ngrok_token}" !COMMANDLINE_ARGS="$ARGS" REQS_FILE="requirements.txt" python launch.py
```


![](https://github.com/shashankmcode/Stable-Diffusion-on-kaggle/raw/main/stable-diffusion-webui/Screenshot%202023-10-27%20104647.png)
