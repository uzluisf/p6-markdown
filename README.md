Example Usage
-------------

    use Text::Markdown;
    use Text::Markdown::to::HTML;
    my $md = Text::Markdown::Document.new($raw-md);
    say $md.render(Text::Markdown::to::HTML);
