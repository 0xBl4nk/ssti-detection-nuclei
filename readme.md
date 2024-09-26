# USAGE
```bash
nuclei -u <url> -t ssti-detection-template.yaml -var param=<url-param>
```
- **`-var param=<url-param>`**: Defines the name of the URL parameter (input) where the SSTI payload will be injected 

# USAGE EXAMPLE
nuclei -u http://localhost:5000/vulnerable -t ssti-detection-template.yaml -var param=input

---

![example-image](https://i.imgur.com/SfBjaHe.png) 
