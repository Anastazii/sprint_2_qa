Описание тестов:

Данные тесты проверяют функционал класса BooksCollector.

test_add_new_book_add_two_books - проверяет добавление новой книги
test_add_same_book_twice - проверяет, что нельзя добавить одну и ту же книгу дважд ы
test_set_book_rating_valid_value_8 - проверяет установку заданного рейтинга, в данном случае 8
test_set_rating_below_1 - проверяет, что нельзя поставить рейтинг ниже 1
test_set_rating_above_10 - проверяет, что нельзя поставить рейтинг выше 10
test_get_books_with_specific_rating_value_8 - проверяет, что по заданному рейтингу возвращается список книг
test_add_book_in_favorites_book1 - проверяет, выбранную книгу можно добавить в избранное
test_delete_book_from_favorites_book1 - проверяет, что книгу можно удалить из избранного
test_get_list_of_favorites_books_book1 - проверяет, что метод возвращает список избранных книг