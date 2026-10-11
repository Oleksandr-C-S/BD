# Laboratory Work 1 — VideoHub

**Student:** Чакун Олександр  
**Group:** ІМ-о51  
**Number in group list:** 18

## Topic

Design of a conceptual ER model for a video hosting platform.

The project models a simplified video hosting service called **VideoHub**.

## Main entities

- `User`
- `Video`
- `Comment`
- `VideoLike`
- `Subscription`

## Project structure

```text
Lab1/
├── screenshots/
│   └── er_diagram.png
├── src/
│   ├── Lab_1.csproj
│   └── Program.cs
├── er_diagram.mmd
├── report_lab1.md
├── report_lab1.pdf
└── README.md
```

## C# model

The `src/Program.cs` file contains C# classes that represent the entities from the ER model.

The program also creates several demo objects to show the relations between users, videos, comments, likes and subscriptions.

## Run

Requirements:

- .NET 8 SDK

Run the project from the repository root:

```bash
dotnet run --project Lab1/src/Lab_1.csproj
```

## Report

The laboratory report is available in two formats:

- `report_lab1.md`
- `report_lab1.pdf`

The ER diagram is stored in:

- `er_diagram.mmd`
- `screenshots/er_diagram.png`
