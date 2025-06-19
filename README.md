# py-4
class Book:
    def __init__(self, book_id, name, cost, publisher):
        self.book_id = book_id
        self.name = name
        self.cost = cost
        self.publisher = publisher
    def display(self):
        print(f"Book ID   : {self.book_id}")
        print(f"Name      : {self.name}")
        print(f"Cost      : ₹{self.cost:.2f}")
        print(f"Publisher : {self.publisher}")
        print("-" * 30)
book1 = Book(101, "The Alchemist", 299.00, "HarperCollins")
book2 = Book(102, "Wings of Fire", 350.50, "Universities Press")
book3 = Book(103, "Python Programming", 450.75, "O'Reilly Media")
book1.display()
book2.display()
book3.display()

