# Ödev - Model Kullanımı
UpdateBook ve GetById metotlarının input ve outputları için model yapsını yazınız. Proje içerisinden Input/Output olarak entity kullanan bir yapının bukunmuyor olması gerekiyor.

```c#
public class UpdateBookModel
{
    public string Title { get; set; }
    public int GenreId { get; set; }
    public int PageCount { get; set; }
    public DateTime PublishDate { get; set; }
}
```

```c#
public class GetByIdBookViewModel
{
    public string Title { get; set; }
    public int PageCount { get; set; }
    public string Genre { get; set; }
    public string PublishDate { get; set; }
}
```


