# Providing drag and drop functionality in selenium python

This is a basic package which provides functionality of drag and drop in python using javascript. It is compatible with youtube, instagram and most of other websites which require drag and drop for pasting/uploading a file.

## How to use?
To use this package you need to first install it using pip, type:

```
pip install 
```

After it's done navigate back to your program and type:

```
import dd-selenium
```

Now for drag and drop you need to use a function from the package, type:

```
dd-selenium.dds(drop_target, path)
```

Replace 'drop_target' with the div you want to drag and drop in and replace 'path' with the file path on your pc.


## Example:

```
import dd-selenium

path = driver.findElement(By.PATH(""));

dd-selenium.dds(path, "C:/abc.file")
```

Thanks for checking out the repo, if you have any issues feel free to ask.

Disclaimer: I am not responsible for any kind of harm caused by the package. 