In this section . I wanna introduce about a app that help you takes note main details in one video and pdf file.
A landing page introduce about website and what you will get when work on .
When login you will follow the  next steps and go to the dashboard.
Today: I created feature create a new folder on dashboard
You can test at website <a> </a>
- Create a page that you can log in from google or a new account ( include email and passwords fields) ;
   => Access token back to get image, username and email from google to show in profile page.
   => Save it at local then get all infor to show on UI DASHBOARD PROFILE
   => Token will stored on browser in some day and after then token will be automatically deleted.
   => Check token on browser and redirect to dashboard page if it existed


- Create modal for profile page: Where you can view detail of your account on the page profile.
   Instruction: When you login from google , google will return token and from token you can request information of user.
   After that, save it on local and show infor of user in profile page.

- Create note page include some tabs : notes, quiz, flashcards, transcript
  + notes: get some main details on a video, pdf ...
  + quiz:  suggest some questions from note that you can remember all infor from notes.
  + flascards: questions and answers when you slip the cards.
  + transcripts: details of notes include all information of note that help you manage and learning fast from reading full papers.

- Create introduce about NoteFlow Ai. Help you understand about it 
  You can access at <a href="https://noteflowai.netlify.app/dashboard/notes/0"></a>


- Every user just create three notes on trial account

- Upload file pdf and create note main detail on dashboard.
- Create authentication process for user. login and logout.
 - Log out feature and session user
 - When user access to dashboard, website redirect to sign in page when token not saved on browser
 - Create some interface to mapping from database to backend.
    + With each table on the database, we will map it on each interface on back end and front end. 
- every user will have three notes for free. Over on three, user have to buy more notes or upgrade to pro with no limitation of feature on this tool.
- User can create new folder and edit folder name as they want.
- Design database and reused component 
- Following all coding standard like : KISS, DRY, SOLID, REFACTORY, REUSED, COMPONENTS
- User can edit , delete folder and add new folder 
- I saw it like folde on your computer. When you create a new folder it will show on sidebar, and many notes on folder.
 - On All notes, it is list of all of notes that you still not grant it to any folder.
 - On each note have assign to folder, you can assign it to any folder.
 And it automatically update again, show on sidebar. When you click on each one folder, it will show all of notes that belong folder.
 - When user is at dashboard page, the user can see amount of notes on each folder.
 Example: On all notes folder will show all notes that belong the user.
   -  Each folder will have some folder related. 


- Today: User can delete folder and edit folder name. => When all action done, folder will automatically update and show it on sidebar

- Each user just create 3 notes for free. When over 3 notes, the user when click on all button that create new note will show pop up upgrade pro for monthly or yearly/
Mình vừa nhìn kỹ UI bạn gửi, thì NoteFlow AI của bạn đã có các ý chính mạnh rồi:

📁 Folder bên trái quản lý ghi chú

📋 Upload audio, pdf, youtube

🧹 Tự động chuyển thành notes sạch sẽ

⚡ Hiện trạng: free 2/3 notes → có upsell plan

👉 Mình đề xuất thêm 5 ý tưởng để mạnh hơn (và có thể scale thành sản phẩm to):

1. Auto Organize (Tự động tổ chức Folder)
Khi upload file hoặc ghi chú mới → AI tự hỏi:

"Bạn muốn lưu vào folder nào?"

Hoặc "Tôi đề xuất bạn lưu vào folder XYZ"

→ Vừa giảm thao tác vừa giúp người dùng cảm thấy thông minh hơn.

2. Magic Link (Kết nối tự động giữa các ghi chú liên quan)
Ví dụ: Trong note về "DeFi", có từ khóa "blockchain" → gợi ý link sang các ghi chú liên quan blockchain.

Giống kiểu Wikipedia nội bộ!

3. Mini Tasks/To-do Extraction
AI scan nội dung ghi chú → tự động detect các task ("cần làm", "hành động", "follow up") → gợi ý thành checklist.

4. Quick Mindmap View
Bấm 1 nút → xem tất cả các note dưới dạng sơ đồ (node -> node), để visualize kiến thức đang có.

5. Flow Reminder
Nếu một note bị bỏ quên lâu (ví dụ 7 ngày), hệ thống gợi ý:

"Bạn có muốn review/update note này không?"

Hoặc "Bạn có muốn link note này với các ý tưởng mới?"

🎯 Tóm lại:

Tính năng mới	Lợi ích
Auto organize folder	Quản lý note thông minh, nhanh
Magic link ideas	Khuyến khích người dùng đọc chéo, hiểu sâu
Todo extraction	Biến ghi chú thành hành động cụ thể
Quick mindmap view	Visualize tất cả ghi chú như sơ đồ tư duy
Flow reminder	Giữ cho notes sống, không chết
💬 Bạn có muốn mình vẽ thêm bản flow UX/UI cho mấy tính năng mở rộng này không?
👉 Nếu thích, mình dựng luôn flow mẫu cho bạn dễ hình dung! 🚀

Bạn có muốn mình làm tiếp không? (Yes/No) 🔥
