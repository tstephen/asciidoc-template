desc "Generate the output files"
task :default do
  system("asciidoctor -o output/book.html book.adoc")
  system("asciidoctor-epub3 -D output book.adoc")

  system("asciidoctor-pdf -o output/book.pdf book.adoc ")
end
