# GoogleA

![Google Assistant + Raspberry Pi](https://cdn.instructables.com/FJ5/M95M/JD0KD411/FJ5M95MJD0KD411.LARGE.jpg)

[Introduction to the Google Assistant Library](https://developers.google.com/assistant/sdk/guides/library/python/)
## Get the scripts!
```
cd;git clone https://github.com/YXY-git-hub/GoogleA.git;
```
## Follow the steps!
* Embed the Google Assistant
  * [Set Up Hardware and Network Access](https://developers.google.com/assistant/sdk/guides/library/python/embed/setup?hardware=rpi)
  * [Configure and Test the Audio](https://developers.google.com/assistant/sdk/guides/library/python/embed/audio)
   ```
   mv GoogleA/arduioRecord/* ~;bash arduioRecordPlay;bash soundT;bash audioT
   ```

  * [Configure a Developer Project and Account Settings](https://developers.google.com/assistant/sdk/guides/library/python/embed/config-dev-project-and-account)
  * [Register the Device Model](https://developers.google.com/assistant/sdk/guides/library/python/embed/register-device)
  * [Install the SDK and Sample Code](https://developers.google.com/assistant/sdk/guides/library/python/embed/install-sample)
  ```
  mv GoogleA/GASDK/* ~;bash pyenv
  ```
  ```
  bash packages;bash credentials
  ```

  * [Run the Sample Code](https://developers.google.com/assistant/sdk/guides/library/python/embed/run-sample)
  ```
  mv GoogleA/runS ~;bash runS
  ```
  
  ## Remove the scripts
  ```
  rm arduioRecordPlay soundT audioT;rm pyenv packages credentials
  ```
