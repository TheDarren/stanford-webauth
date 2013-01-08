stanford-webauth
================

Stanford specific WebAuth configuration for RHEL 5/6, and Debian.  For
general information about WebAuth, see:

    http://webauth.stanford.edu

This module assumes:

- You have the wallet module and the WebAuth keytab can be downloaded by using
  the server's host keytab with wallet. 

- You have Stanford repositories configured for RHEL to have access to the
  stanford-webauth package.  stanford-webauth is available in Debian/Debian
  backports.

- You have apache installed and configured to some sane defaults.

License

The Stanford WebAuth puppet module is released under the following license:

    Copyright 2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012,
    2013 The Board of Trustees of the Leland Stanford Junior University.

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the "Software"),
    to deal in the Software without restriction, including without limitation
    the rights to use, copy, modify, merge, publish, distribute, sublicense,
    and/or sell copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
    DEALINGS IN THE SOFTWARE. 
