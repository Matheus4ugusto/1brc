# 1 Billion rows challenge

---

## What's it?

This code performs a challenge of reading, extracting data and sorting the extracted data from a 1 billion line txt file.

---

## How can I execute it on my machine?

You can execute it on your machine first typing the following command on the terminal:

**Note: If you want to create a file with one billion lines, make sure you have at least 15GB free on your disk**

```
python3 create.py [number of lines that you want to generate]
```

After populating the file measurements.txt, you can execute the following command and wait:

```
go run main.go
```

The output should be something like a lot of places, the min temp, the medium temp, the max temp and in the end of the output, it should have how many time it spent to read, extract and sort that data.