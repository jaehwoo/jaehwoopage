# CV

<!--- file: docs/howto/embedding_pdf.md --->
<pdf_file = "CV-2.pdf">
<solid_filepdf = '<i class="fas fa-file-pdf"></i>'>
<empty_filepdf = '<i class="far fa-file-pdf"></i>'>

## Example: Embedding a PDF file

<object data="CV-2.pdf" type="application/pdf">
    <embed src="CV-2.pdf" type="application/pdf" />
</object>

## Example: Creating a link to a PDF file

<a href="{{ pdf_file }}" class="image fit">{{ solid_filepdf }}</a>

{% endwith %}