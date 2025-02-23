### Challenge files for DO NOT REDEEM series

<!--- Couldn't find a better place to put these files --->

To download and decompress the archive's contents:
```sh
git clone https://github.com/savsch/chall.git
cd chall
git lfs install
git lfs pull
mkdir extracted
cat kitler\'s-phone.tgz-part* | tar -xzf - -C extracted
```

#### Unrelated to the challenge
For more on git lfs, check out https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage
