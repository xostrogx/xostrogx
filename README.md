```bash
user@xostrogx:~/qa-resume$ python3 resume.py --info
===========================================================
>>> JUNIOR QA ENGINEER <<<
===========================================================
[→] Executing...
```
```bash
Hi! I'm Dima (@xostrogx)
Role: Junior QA -> Trainee Automation
Target: Manual QA -> Automation -> DevOps
-----------------------------------------------------------
QA practice: 7 months (educational)
Production: 16 years
Networking: 6 years
-----------------------------------------------------------
Looking for: Junior QA -> Trainee Automation
```
[✓] Profile loaded

```bash
user@xostrogx:~/qa-resume$ tools --list --icons
===========================================================
>>> SOME TOOLS I USE <<<
===========================================================
[→] Loading tools...
```

$ tools --icons

=======================================================================

<p >
  <!-- Bash -->
  <img height="32" src="/images/icon/bash.svg" alt="Bash" title="Bash" />
  <!-- Git -->
  <img height="32" src="/images/icon/git.svg" alt="Git" title="Git" />
  <!-- VS Code -->
  <img height="32" src="/images/icon/vscode.svg" alt="VS Code" title="VS Code" />
  <!-- Ubuntu -->
  <img height="32" src="/images/icon/ubuntu.svg" alt="Ubuntu" title="Ubuntu" />
  <!-- MySQL -->
  <img height="32" src="/images/icon/mysql.svg" alt="MySQL" title="MySQL" />
  <!-- MongoDB -->
  <img height="32" src="/images/icon/mongodb.svg" alt="MongoDB" title="MongoDB" />
  <!-- Charles Proxy -->
  <img height="32" src="/images/icon/charles.svg" alt="Charles Proxy" title="Charles Proxy" />
  <!-- Postman -->
  <img height="32" src="/images/icon/postman.svg" alt="Postman" title="Postman" />
  <!-- DevTools -->
  <img height="32" src="/images/icon/devtools.svg" alt="DevTools" title="DevTools" />
  <!-- Figma -->
  <img height="32" src="/images/icon/figma.svg" alt="Figma" title="Figma" />
  <!-- Qase -->
  <img height="32" src="/images/icon/qase.svg" alt="Qase" title="Qase" />
  <!-- Jira -->
  <img height="32" src="/images/icon/jira.svg" alt="Jira" title="Jira" />
  <!-- TestRail -->
  <img height="32" src="/images/icon/testrail.svg" alt="TestRail" title="TestRail" />
  <!-- YouTrack -->
  <img height="32" src="/images/icon/youtrack.svg" alt="YouTrack" title="YouTrack" />
</p>

=======================================================================

[✓] 14/14 tools loaded


```bash
user@xostrogx:~/qa-resume$ cat resume.py
===========================================================
>>> DETAILS <<<
===========================================================
[→] Loading source code...
```

```python
class JuniorQAEngineer:

    def __init__(self):
        self.username = 'xostrogx'
        self.name = 'Dima'
        self.role = ['Junior QA', 'Trainee Automation']
        self.language_spoken = ['ru_RU', 'en_RU']
        
        self.skills = {
            'manual_testing': ['test_cases', 'checklists', 'bug_reports', 'exploratory_testing'],
            'api_testing': ['Postman', 'REST', 'SOAP', 'Charles_Proxy'],
            'databases': ['MySQL', 'MongoDB'],
            'tools': ['Jira', 'Qase', 'Git', 'Linux'],
            'learning': ['Python', 'pytest', 'CI/CD', 'Selenium']
        }
        
        self.experience = {
            'qa_practice': '7 months (educational)',
            'production': '16 years',
            'networking': '6 years',
            'commercial_qa': '0 (honestly)'
        }
```
[✓] Code loaded
```bash
user@xostrogx:~/qa-resume$ ls test-artifacts/
===========================================================
>>> TEST ARTIFACTS <<<
===========================================================
[→] Loading artifacts...
```

$ --test  |  [~/web_testing](https://github.com/xostrogx/web_testing)

$ api --rest --soap  |  [~/api_testing](https://github.com/xostrogx/api_testing)

$ mysql --query --validate  |  [~/mysql](https://github.com/xostrogx/mysql)

$ android --manual --bugreport  |  [~/mobile_testing](https://github.com/xostrogx/mobile_testing/)

[✓] 4/4 artifacts loaded 

```bash
user@xostrogx:~/qa-resume$ ls contacts/
===========================================================
>>> CONTACTS <<<
===========================================================
[→] Fetching contact information...
```

$ hh --resume  |  [~/hh/resume/xostrogx](https://voronezh.hh.ru/resume/7833b707ff0e0d02440039ed1f78394f76546b)

$ telegram --contact  |  [@xostrogx](https://t.me/xostrogx)

$ email --contact  |  [xostrogx@mail.ru](xostrogx@mail.ru)

[✓] All contacts loaded successfully

```bash
user@xostrogx:~/qa-resume$ exit
logout
```