* ����������:

Microsoft.EntityFramework 6.4.4 - ���������� ��� ����������� ������������ � ���������� ����������

Microsoft.EntityFrameworkCore.SqlServer 3.1.1 - ���������� ��� ������������� ���� ������

Microsoft.AspNetCore.Mvc.NewtonsoftJson 3.1.0 - ���������� � ������� �������� ��� ������ ����������� � ����� ������ � json-�������

Newtonsoft.Json 13.0.2 - ���������� ��� ������������� Json

Telegram.Bot.Framework 1.1.4 - ���������� ��� �������� �������� ����

Microsoft.EntityFrameworkCore.Tools - 3.1.0 - ���������� ��� ������������� ������ ��� ���� ������


* ������� ��������� - .NET Core 3.1


*����� �����:

Controllers - �������� ���������� � API-�������� ��� ������ � ����� ������ �� ������� ����������

DataDbContext - �������� ����� ��������������� ������ ������ � ����� ������


*������ ��������������: 

���������� ���������� WpfApplication.exe
������������:
 - �������������, �����: admin, ������: admin
 - ��������, �����: manager, ������: manager


API �������:

 - Get-�������:

	https://localhost:44373/webapi - ���������� ������ ���� ������

	https://localhost:44347/webapi/id - ���������� ������ �� ��������� id

 - Post-������:

	https://localhost:44373/webapi/AddRequest - ���������� ������ � ���� ������

 - Put-������:

	https://localhost:44373/webapi/UpdateRequest - ��������� ������� ������

 - Delete-������:

	https://localhost:44373/webapi/DeleteRequest/id - �������� ������ �� id

�������:

 WpfApplication:

 - Get-������:

	https://localhost:44373/webapi/GetRequests - ���������� ��� ������

 - Put-������:

	https://localhost:44373/webapi/Update - ��������� ������ ������

 Website:

 - Post-������:

	https://localhost:44373/webapi/AddRequest - ��������� ������ � ���� ������

 TelegrammBot:

 - Get-������:

	https://localhost:44373/webapi/GetRequests - ���������� ������ ������