a = input("Wie heißt du?")


jahr = 2025

alter = int(input(f"Wie alt bist du {a}?"))
geburtsjahr = jahr - alter
if alter >= 10 <100:
    print("Du bist reif genug so gebe ich dir eine antwort")
    print(f"Du bist {jahr - alter} geboren")

else:
    b = alter <= 10
    print("Zu Jung! "
          "Damit ich dir eine Antwort gebe musst du 10 oder älter sein")
if alter >100:
    print("Zu ALT")

