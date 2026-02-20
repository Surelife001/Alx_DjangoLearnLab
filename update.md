# Update the title of “1984” to “Nineteen Eighty-Four” and save the changes.

book = Book.objects.get()
book.title = "Nineteen Eighty-Four"
book.save()

# Output:
<QuerySet [<Book: Nineteen Eighty-four>]>