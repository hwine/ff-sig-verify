=========
Test Data
=========

This directory contains various test data, and pre-computed lambda
events:


    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | Size      | Name                      | Description                                                                                      |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 781648    | 2020-05-32bit.exe         | Header only, 2020-05 cert (bz 1634577), should pass                                              |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 246056    | S3_event_template.json    | Fx stub installer, "new" Authenticode key, should pass                                           |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 246056    | 32bit.exe                 | Fx installer, "old" Authenticode key, should pass                                                |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 243336    | 32bit_new.exe             | Fx stub installer, "new" Authenticode key, should pass                                           |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 50109504  | 2019-06-64bit.exe         | Fx installer, Authenticode key as of bug 1554767, should pass                                    |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 492112    | bad_1.exe                 | bad signature                                                                                    |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 246056    | bad_2.exe                 | bad signature                                                                                    |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 266136    | PostBalrogStub.exe        | Fx stub installer, after Balrog manipulation (need not pass for lambda, but should pass for CLI) |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    |   8893    | S3_event_template.json    | Sample "aws lambda invoke" template                                                              |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 431296    | signtool.exe              | good signature, but not Mozilla                                                                  |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 494272    | vswriter.exe              | good signature, but not Mozilla                                                                  |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 333088    | FxStub-87.0b2.exe         | Fx stub installer, timestamp uses sha2 hash                                                      |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
    | 14032     | 2021-05-signable-file.exe | File signed with new key as of bug 1703321, should pass                                          |
    +-----------+---------------------------+--------------------------------------------------------------------------------------------------+
