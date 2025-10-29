🌱 Planto

Planto is a smart reminder app that helps you take better care of your plants.
Easily add your plants, set their watering, sunlight, and environment preferences, and let Planto remind you exactly when it’s time to give them some love 🌤️💧.

✨ Features

* 🪴 Add & Manage Plants – Keep track of all your plants in one beautiful interface.
* 💧 Smart Watering Reminders – Never forget to water your plants again! Get notifications when it’s time.
* ☀️ Custom Plant Settings – Choose how much water, sunlight, and care each plant needs.
* ✏️ Edit Anytime – Update a plant’s details as it grows or its environment changes.
* 🔔 Push Notifications – Receive timely reminders so your plants always stay healthy.



📱 Screenshots

![Start your plant journey!](https://github.com/user-attachments/assets/dedd6e37-f70d-46b9-847a-f944c80d87ba) ![Today Reminder](https://github.com/user-attachments/assets/4b781153-62d8-4cdb-ad64-c25b84f4cd89)![Set Reminder](https://github.com/user-attachments/assets/2f5a5d54-6217-4786-9dad-484fb67fbadc)






🚀 Getting Started

🧭 Project Structure

Plant/
├── Model/
│   └── PlantModel.swift                Defines the Plant data model
│
├── View/
│   ├── AllRemindersCompleted.swift     View displayed when all reminders are done
│   ├── EditView.swift                  Allows editing plant details
│   ├── MyPlantsView.swift              Displays user’s list of plants
│   ├── NotificationManager.swift       Handles local notifications and scheduling
│   ├── PlantListView.swift             Shows all plants in a list
│   └── SetReminderView.swift           UI for setting watering reminders
│
├── ViewModel/
│   ├── MyPlantsViewModel.swift         Logic for managing user's plants
│   ├── PlantListViewModel.swift        Handles data flow for plant lists
│   └── SetReminderViewModel.swift      Manages reminder scheduling logic
│
├── Assets/                             App icons, colors, and other resources
├── Media/                              Images, illustrations, and plant photos
└── PlantApp.swift                      App entry point and SwiftUI setup




🔔 Notifications

Planto uses local notifications to remind you when a plant needs watering.
Its a customized reminder based on each plant’s care schedule.


🛠️ Built With

⚛️ Xcode — for building the app

  
🤝 Contributing

Contributions, bug reports, and feature requests are always welcome!
Feel free to open an issue or submit a pull request.


