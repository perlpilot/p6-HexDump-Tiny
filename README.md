= Name =

HexDump::Tiny

= Synopsis =

    #!/usr/bin/env perl6

    use HexDump::Tiny;

    my $s = slurp("filename");
    .say for hexdump($s);

= Description =
