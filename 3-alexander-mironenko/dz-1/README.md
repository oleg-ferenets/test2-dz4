������� ��������� ��-1

1 - �� ��������� �������:
	git clone https://github.com/Evan-Kork/temabit-lections-2019.git
	������� ���������� �� ��� ��.
2 - $ cd temabit-lections-2019
	# �� ��������� ������� 'cd' ���������� � ����� ���������� � ���� 
	������� ���������
3- $ git checkout -b feature/3-alexander-mironenko/dz-1 
	# ��������� ���� ���� 3-alexander-mironenko/dz-1, 
	�� ����������� ������������� �� ��
4-$ git status - ����� ����������� ����� ��� ���� ���������� ��������
	3-alexander-mironenko/
5-$ git add . # ���������� ����� �� ��� �� � ��
6-$ git status - ����� � ������ (new file:   3-alexander-mironenko/dz-1/README.md)
 	���������� �������, �� �������� ��� ��������� �� ������� commit

7-$ git commit -m "my first commit" - �������� �� �������� "��������"
8-$ git push origin feature/3-alexander-mironenko/dz-1
	#������������ ������� ����� � ���� ���� �� ����������




	������� git
* git init         - �������� ����������� .git, ������������� �����������.
* git clone remote - ����������� �����������.
* git status       - �������� ��������� ���������� �����������
* git add          - �������� ���������� ������
    1. .           - ����� � ����� �� ����� ������ � ������
    2. '*'         - ��� ����� � ����� �� ���� �������
* git commit
    1. -m 'message' - ��������� ����� ��������
    2. --amend -m   - �������� ��������� commit
* git push 
    1. -u origin master             - ��� � ��������� origin � ����� master
    2. --set-upstream origin master - ������������� ��������� ����� �� ���������
* git pull                  - ��������� ��������� ��������� � �����������
* git fetch remote          - ���������� ���������� � ��������� ����������
* git merge branch          - ������ �����
### ���������� � config � log
* git config       
    1. --global user.name  - ��������� ��������� ��� �����
    2. --global user.email - ��������� ��������� email.user
    3. --list              - ����� �������� config
* git log
    1. --pretty=oneline:                      - ����� � ���� ������
    2. --pretty=format:"%h - %s | [%ad][%an]" - ��������������� �����
* git remote 
    1. show origin - ���������� ��� ��������� �����������
    2. -v          - ����������� ������

### ������ � �������
* git checkout 'name_branch' - ������������� �� ����� name_branch
    1. -B 'name_branch'      - �������� ����� � ������������� �� ����� name_branch
* git branch                 - ������ ��������� �����
    1. 'name-branch'         - �������� �����
    2. -D                    - ������� ����� (������ ��������)
* git reset                  - ����� ���������
    1. @~                    - ���������� commit
    2. %h                    - ��� commit ��� ��������
* git reflog branch          - ����� ��������� ��������
* git cherry-pick %h         - �������� commit