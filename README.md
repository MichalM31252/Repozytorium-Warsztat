# 📘 Podstawowe komendy GIT

```bash
# 🔧 Inicjalizacja repozytorium
git init
# Tworzy nowe lokalne repozytorium Git w aktualnym folderze.

# ➕ Dodawanie plików do śledzenia
git add .
# Dodaje wszystkie pliki i foldery w bieżącym katalogu do systemu kontroli wersji.

# 💬 Tworzenie commita
git commit -m "Opis commita"
# Tworzy commit, czyli zapis zmian, wraz z opisem tego, co zostało zmienione.

# 🚀 Wysyłanie zmian do zdalnego repozytorium
git push
# Wysyła nasze lokalne zmiany do zdalnego repozytorium (np. GitHub).

# 📥 Klonowanie repozytorium
git clone https://github.com/MichalM31252/Repozytorium-Warsztat.git
# Pobiera całe repozytorium do aktualnego folderu lokalnego.

# 🗑️ Usunięcie ostatniego commita
git reset --hard HEAD~1
# Usuwa ostatni commit i przywraca pliki do stanu sprzed niego.

git push origin main --force
# Wymusza aktualizację zdalnego repozytorium, aby odzwierciedlić lokalne zmiany.
