This is a simple way To Deploy it in github pages:

1. **Make Git trust your folder**:
   Run this(in my Case):
   ```bash
   git config --global --add safe.directory "C:/Users/braag/Desktop/For Computing Studies/CPIT-405 Web Applacation/Lab/Lab eight/lab8"
   ```

3. **Connect to GitHub**:
   Set up GitHub as your remote:
   ```bash
   git remote add origin https://github.com/Techiewicky/lab8.git
   ```

4. **Save your changes**:
   Add and commit your files:
   ```bash
   git add .
   git commit -m "Initial commit"
   ```

5. **Deploy**:
   Deploy it to GitHub Pages:
   ```bash
   npm run deploy
   ```

Done! 🎉 This should get your site live on GitHub Pages.
