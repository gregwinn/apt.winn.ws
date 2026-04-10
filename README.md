# apt.winn.ws

APT repository for the [Winn programming language](https://winn.ws).

## Usage

```sh
curl -fsSL https://winn.ws/gpg.key | sudo gpg --dearmor -o /usr/share/keyrings/winn.gpg
echo "deb [signed-by=/usr/share/keyrings/winn.gpg] https://gregwinn.github.io/apt.winn.ws stable main" | sudo tee /etc/apt/sources.list.d/winn.list
sudo apt update && sudo apt install winn
```
