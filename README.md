# win32-getdefaultbrowser-perl
Perl 5 module to return full path to default browser on Windows systems

Brandon Bourret (phatwares@cpan.org)

SYNOPSIS

use Win32::GetDefaultBrowser;
 
my $default_browser = get_default_browser;

Pollutes the namespace with one function: get_default_browser.

METHODS

get_default_browser

Returns the full path to the default browser on a Windows system. Falls back to Internet Explorer on failure.

Version History

1.00 - Initial Release

1.01 - Added Windows 10 support (hopefully)

1.02 - Fixed this POD document

1.03 - More documentation fixes

Permission is granted to use this software under the same terms as Perl itself.

Refer to the Perl Artistic license for details.
