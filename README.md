# Poster template for University of Ottawa

This template can be used for the LaTeX tikzposter class and create a poster that conforms to the specifications as outlined on the [uOttawa Brand website](https://www.uottawa.ca/brand/visual-identity/uottawa-template-spec-sheets).

## Usage
To use, include the following:

    \include{uottawa_poster}
    \titlegraphic{\includegraphics[height=10em]{uottawa_ver_wg9_cmyk}}

The uOttawa colour logo can be downloaded from https://www.uottawa.ca/brand/download-logos

A bleed can be specified by defining a bleed size before the ``\include{uottawa_poster}`` command as follows:

    \def\posterbleed{3mm}

Faculty colours can be automatically applied by specifying the faculty as

    \def\posterfaculty{science}

The possible values are

  * ``arts``
  * ``civillawandcommonlaw``
  * ``engineering``
  * ``education``
  * ``graduateandpostdoctoralstudies``
  * ``healthsciences``
  * ``telferschoolofmanagement``
  * ``medicine``
  * ``science``
  * ``socialsciences``
