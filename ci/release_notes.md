# Bugs

Connection was frequently dropping between eu-east-1 and eu-west-1 when 1 tunnel would go down during rekeying. Setting rp_filter=2 prevents this from making the connection drop completely.
