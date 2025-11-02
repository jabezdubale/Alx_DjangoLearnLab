b = Book.objects.get(id=book.id)
b.title, b.author, b.publication_year

<!-- ('1984', 'George Orwell', 1949) -->