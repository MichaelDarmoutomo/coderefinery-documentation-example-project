# Coderefinery Documentation Example Project
Coderefinery Documentation Example Project is a project to practise writing README files. The main code can be found in `analyse_spreadsheet.py`. The script loads an .xlxs file containing temperatures, prints the column names and returns the mean temperature.

# Usage
You can run `analyse_spreadsheet.py` directly. The console will ask for the path to the excel file.

```{bash}
python3 analyse_spreadsheet.py
```

# Installation
It is recommended to clone the repository.

```{bash}
git clone https://github.com/MichaelDarmoutomo/coderefinery-documentation-example-project.git
```

# Requirements
pandas

```{bash}
pip install -r requirements.txt
```

# Example
```{bash}
$ python3 analyse_spreadsheet.py
>> Provide the name of the excel file you want to analyse:
>> blablabla.xlsx
>> ['Date', 'Temperature']
>> 21.8
```

# License
[Apache](https://github.com/MichaelDarmoutomo/coderefinery-documentation-example-project/blob/main/LICENSE)
