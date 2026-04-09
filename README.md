# tensorivirtauksia
Tässä kansiossa on käytännöllistä tekoälyn toimintaperiaatteeseen ja tensoreihin liittyvää esimerkkikoodia (example code about AI).

## Asennus (installation)

Tama projekti on testattu Windowsissa Python 3.11 -ymparistossa.

## How to get it to work on Windows

### 1. Install Python 3.11 with Python Manager

Open PowerShell and run:

```powershell
py install 3.11
```

Check that Python 3.11 is available:

```powershell
py -0p
```

You should see a Python 3.11 entry in the list.

If `py install 3.11` does not work on your machine, install Python 3.11 first and then continue with the steps below.

### 2. Open the project folder

In PowerShell:

```powershell
cd E:\Git\koulu\dev\tensorivirtauksia
```

### 3. Create a virtual environment with Python 3.11

```powershell
py -3.11 -m venv .venv
```

### 4. Activate the virtual environment

```powershell
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks script execution, run this once in the same terminal:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then activate the environment again:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 5. Upgrade pip

```powershell
python -m pip install --upgrade pip
```

### 6. Install the project dependencies

```powershell
python -m pip install -r requirements.txt
```

### 7. Run the program

```powershell
python .\ml_25_eye_off.py
```

## Käyttö (usage)

Käskyn `python .\ml_25_eye_off.py` (give the command)

myötä seuraava käyttöliittymä tulee näkyviin (and you will see an user interface): 

![image](https://github.com/user-attachments/assets/9b10f8fc-e560-4c86-b88c-baffe867e029)

...kokeile painaa eri painikkeita, tee valintoja ja huomaat pian ratkaisun toimintaperiaatteen - voit tallentaa
käyttöliittymällä helposti dataa eri kansioihin ja tutustua tämän itse kerätyn aineiston avulla vaikkapa koneoppimisen perusteisiin.

(test the buttons and checkboxes and you soon will get the gist of the example)

## Miksi repon nimi on "tensorivirtauksia" (why the name "tensori" in the repository)

Esimerkki havainnollistaa miten tensori virtaa vasemmalta oikealle ja kohtaa matkalla erilaisia jännittäviä vaiheita.

(the example illustrate the flow of tensors in a simple AI-model case)


## How to get it to work

Summary:
Install python 3.11

- py install 3.11

Go to the project folder

- py -3.11 -m venv .venv
- .\.venv\Scripts\Activate.ps1
- python -m pip install --upgrade pip
- python -m pip install -r requirements.txt
- python .\ml_25_eye_off.py

