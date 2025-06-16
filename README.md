# Differential Cryptanalysis on a Toy S-box

The Python script outputs a **differential distribution table**, which shows how specific input differences result in certain output differences with varying probabilities. This is useful for analyzing the strength of an S-box against differential cryptanalysis.

## Background on Differential Cryptanalysis

Differential cryptanalysis is a type of chosen-plaintext attack that examines how specific differences in input pairs influence the differences in their corresponding outputs, helping to identify patterns and potential weaknesses in cryptographic algorithms.

## Usage

1. Make sure you have Python 3 installed on your system.  
2. Clone this repository or download the script.  
3. Run the script from your terminal or command prompt:

```
python differential_cryptanalysis.py
```

4. The output will be a table showing the differential distribution for the toy S-box.

## Files

- `differential_cryptanalysis.py`: The main Python script performing the analysis.

## Credits

This project was developed with assistance from ChatGPT (OpenAI) as part of a cryptography learning journey.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
