# OpenRV 3.2.0 Windows Cloud Build

Upload the `.github` folder to the root of your GitHub repository.

Then:
1. Open the repository on GitHub.
2. Click Actions.
3. Select "Build OpenRV 3.2.0 Windows x64".
4. Click "Run workflow".
5. Wait for the build.
6. Open the completed run and download the artifact named:
   OpenRV-3.2.0-Windows-x64

If the build fails, download the GitHub Actions log archive or copy the failed step output and send it to ChatGPT.

This workflow builds the official AcademySoftwareFoundation/OpenRV v3.2.0 tag.
It is a first-pass CI workflow and may require a targeted dependency patch if upstream dependencies fail on the current hosted runner.
