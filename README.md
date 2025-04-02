## Building the Web Application

1. Ensure you're in the project root directory:

   ```bash
   cd /path/to/whoarewe_flutter
   ```

2. Build the web application:

   ```bash
   fvm flutter build web --release
   ```

3. Copy the build files to the deployment folder:

   ```bash
   # Remove existing files in deployment folder
   rm -rf deployment/*

   # Copy new build files to deployment folder
   cp -r build/web/* deployment/
   ```

4. The built files will now be available in the `deployment` directory.
