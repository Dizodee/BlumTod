## BLUM BOT

## BOT FEATURE

- Auto Play Game
- Auto Claim Daily
- Auto Task
- Auto farming
- Multi Account
- Proxy Support

## COMMANDS
1. **Installation**
   ```bash
   git clone https://Dizodee/Blumnew.git
   cd Blum-Bot
   pip install -r requirements.txt
   ```
2. **Configuration**
To Adjust GamePoint, Enable/Disble Tasks, etc..
```bash
nano config.json
```
```json
{
  "game": true,
  "daily": true,
  "task": true,
  "farming": true,
  "low_point": 2600000,
  "high_point": 2800000,
  "thread": 1,
  "proxy": false,
  "delay_account_switch": 10,
  "delay_loop": 3000
}
```
3. **ADD ACCOUNTS**
   ```
   nano query.txt
   ```
   
4. **Set Up Proxy (Optional)**  
   To use a proxy, create a `proxy.txt` file and add proxies in the format:

   ```
   http://username:password@ip:port
   ```

   - Only HTTP and HTTPS proxies are supported.
   
5. **START THE BOT**
```bash
python main.py
```
## Buy ME a Coffee

- **BINANCE UID:** 
836899445

## Reach me on whatsapp
https://wa.me/254111200187

