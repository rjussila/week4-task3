# week4-task3

subtask1
- <img width="2502" height="104" alt="Näyttökuva 2026-10-02 113654" src="https://github.com/user-attachments/assets/6e810fdc-2efc-4198-bf89-aa3aff1158e7" />
- <img width="996" height="966" alt="Näyttökuva 2026-10-02 113743" src="https://github.com/user-attachments/assets/d2111670-a4b7-4848-af89-419fad988ae1" />

subtask2
- The cookie generation depends on the timestamp as the dvwasession cookie number increases according to time went between send. in the picture the last part of the number is 545 and next one i got was 1790930909 so it was created 364 seconds later.
- <img width="2010" height="1168" alt="Näyttökuva 2026-10-02 114405" src="https://github.com/user-attachments/assets/2ceb7372-e5ec-4dcd-9a9c-ae9b5b6a4b00" />

subtask3
- As i check the ones succesfull they were the ones with 4740 or 4745 byte length. These ones were gordonb/abc123 and admin/password. There are screenshot from the one that will let us in as "welcome to the password protected area gordonb".
- <img width="2562" height="1150" alt="Näyttökuva 2026-10-02 121037" src="https://github.com/user-attachments/assets/c7b1068b-2726-4234-9837-eafda6da9d36" />
- <img width="1992" height="948" alt="Näyttökuva 2026-10-02 121634" src="https://github.com/user-attachments/assets/4197ab1f-f616-407c-9211-af50661bf8b5" />

subtask4
- <img width="1598" height="1386" alt="Näyttökuva 2026-10-02 164337" src="https://github.com/user-attachments/assets/158e3004-6680-40c2-b892-198ec64b02ae" />

subtask5
- command: docker run --network="host" vanhauser/hydra -V -f -I -l admin -x 4:4:a "http-get-form://localhost/vulnerabilities/brute/:username=^USER^&password=^PASS^&Login=Login:H=Cookie:PHPSESSID=ocqp9kkrqr1bcu6sq61cpqakg2; security=low:F=Username and/or password incorrect."
- it took almost 9 minutes to get the password
- <img width="2296" height="272" alt="Näyttökuva 2026-10-02 214507" src="https://github.com/user-attachments/assets/0548a983-ab6d-4021-b7db-b1fa484ad005" />

