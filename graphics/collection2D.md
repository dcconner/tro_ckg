%!PS-Adobe-3.0 EPSF-3.0
%%Creator: Mayura Draw, Version 4.3
%%Title: collection2D.md
%%CreationDate: Sun Feb 17 22:43:35 2008
%%BoundingBox: -7 675 192 794
%%DocumentFonts: TimesNewRomanPSMT
%%Orientation: Portrait
%%EndComments
%%BeginProlog
%%BeginResource: procset MayuraDraw_ops
%%Version: 4.3
%%Copyright: (c) 1993-2003 Mayura Software
/PDXDict 100 dict def
PDXDict begin
% width height matrix proc key cache
% definepattern -\> font
/definepattern { %def
  7 dict begin
    /FontDict 9 dict def
    FontDict begin
      /cache exch def
      /key exch def
      /proc exch cvx def
      /mtx exch matrix invertmatrix def
      /height exch def
      /width exch def
      /ctm matrix currentmatrix def
      /ptm matrix identmatrix def
      /str
      (xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
      def
    end
    /FontBBox [ %def
      0 0 FontDict /width get
      FontDict /height get
    ] def
    /FontMatrix FontDict /mtx get def
    /Encoding StandardEncoding def
    /FontType 3 def
    /BuildChar { %def
      pop begin
      FontDict begin
        width 0 cache { %ifelse
          0 0 width height setcachedevice
        }{ %else
          setcharwidth
        } ifelse
        0 0 moveto width 0 lineto
        width height lineto 0 height lineto
        closepath clip newpath
        gsave proc grestore
      end end
    } def
    FontDict /key get currentdict definefont
  end
} bind def

% dict patternpath -
% dict matrix patternpath -
/patternpath { %def
  dup type /dicttype eq { %ifelse
    begin FontDict /ctm get setmatrix
  }{ %else
    exch begin FontDict /ctm get setmatrix
    concat
  } ifelse
  currentdict setfont
  FontDict begin
    FontMatrix concat
    width 0 dtransform
    round width div exch round width div exch
    0 height dtransform
    round height div exch
    round height div exch
    0 0 transform round exch round exch
    ptm astore setmatrix

    pathbbox
    height div ceiling height mul 4 1 roll
    width div ceiling width mul 4 1 roll
    height div floor height mul 4 1 roll
    width div floor width mul 4 1 roll

    2 index sub height div ceiling cvi exch
    3 index sub width div ceiling cvi exch
    4 2 roll moveto

    FontMatrix ptm invertmatrix pop
    { %repeat
      gsave
        ptm concat
        dup str length idiv { %repeat
          str show
        } repeat
        dup str length mod str exch
        0 exch getinterval show
      grestore
      0 height rmoveto
    } repeat
    pop
  end end
} bind def

% dict patternfill -
% dict matrix patternfill -
/patternfill { %def
  gsave
    eoclip patternpath
  grestore
  newpath
} bind def

/img { %def
  gsave
  /imgh exch def
  /imgw exch def
  concat
  imgw imgh 8
  [imgw 0 0 imgh neg 0 imgh]
  /colorstr 768 string def
  /colorimage where {
    pop
    { currentfile colorstr readhexstring pop }
    false 3 colorimage
  }{
    /graystr 256 string def
    {
      currentfile colorstr readhexstring pop
      length 3 idiv
      dup 1 sub 0 1 3 -1 roll
      {
        graystr exch
        colorstr 1 index 3 mul get 30 mul
        colorstr 2 index 3 mul 1 add get 59 mul
        colorstr 3 index 3 mul 2 add get 11 mul
        add add 100 idiv
        put
      } for
      graystr 0 3 -1 roll getinterval
    } image
  } ifelse
  grestore
} bind def

/arrowhead {
  gsave
    [] 0 setdash
    strokeC strokeM strokeY strokeK setcmykcolor
    2 copy moveto
    4 2 roll exch 4 -1 roll exch
    sub 3 1 roll sub
    exch atan rotate dup scale
    arrowtype
    dup 0 eq {
      -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 1 eq {
      0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 2 eq {
      -6 -6 rmoveto 6 6 rlineto -6 6 rlineto
      -1.4142 -1.4142 rlineto 4.5858 -4.5858 rlineto
      -4.5858 -4.5858 rlineto closepath fill
    } if
    dup 3 eq {
      -6 0 rmoveto -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 4 eq {
      -9 0 rmoveto 0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 5 eq {
      currentpoint newpath 3 0 360 arc
      closepath fill
    } if
    dup 6 eq {
      2.5 2.5 rmoveto 0 -5 rlineto -5 0 rlineto 0 5 rlineto
      closepath fill
    } if
    pop
  grestore
} bind def

/setcmykcolor where { %ifelse
  pop
}{ %else
  /setcmykcolor {
     /black exch def /yellow exch def
     /magenta exch def /cyan exch def
     cyan black add dup 1 gt { pop 1 } if 1 exch sub
     magenta black add dup 1 gt { pop 1 } if 1 exch sub
     yellow black add dup 1 gt { pop 1 } if 1 exch sub
     setrgbcolor
  } bind def
} ifelse

/RE { %def
  findfont begin
  currentdict dup length dict begin
    { %forall
      1 index /FID ne { def } { pop pop } ifelse
    } forall
    /FontName exch def dup length 0 ne { %if
      /Encoding Encoding 256 array copy def
      0 exch { %forall
        dup type /nametype eq { %ifelse
          Encoding 2 index 2 index put
          pop 1 add
        }{ %else
          exch pop
        } ifelse
      } forall
    } if pop
  currentdict dup end end
  /FontName get exch definefont pop
} bind def

/spacecount { %def
  0 exch
  ( ) { %loop
    search { %ifelse
      pop 3 -1 roll 1 add 3 1 roll
    }{ pop exit } ifelse
  } loop
} bind def

/WinAnsiEncoding [
  39/quotesingle 96/grave 130/quotesinglbase/florin/quotedblbase
  /ellipsis/dagger/daggerdbl/circumflex/perthousand
  /Scaron/guilsinglleft/OE 145/quoteleft/quoteright
  /quotedblleft/quotedblright/bullet/endash/emdash
  /tilde/trademark/scaron/guilsinglright/oe/dotlessi
  159/Ydieresis 164/currency 166/brokenbar 168/dieresis/copyright
  /ordfeminine 172/logicalnot 174/registered/macron/ring
  177/plusminus/twosuperior/threesuperior/acute/mu
  183/periodcentered/cedilla/onesuperior/ordmasculine
  188/onequarter/onehalf/threequarters 192/Agrave/Aacute
  /Acircumflex/Atilde/Adieresis/Aring/AE/Ccedilla
  /Egrave/Eacute/Ecircumflex/Edieresis/Igrave/Iacute
  /Icircumflex/Idieresis/Eth/Ntilde/Ograve/Oacute
  /Ocircumflex/Otilde/Odieresis/multiply/Oslash
  /Ugrave/Uacute/Ucircumflex/Udieresis/Yacute/Thorn
  /germandbls/agrave/aacute/acircumflex/atilde/adieresis
  /aring/ae/ccedilla/egrave/eacute/ecircumflex
  /edieresis/igrave/iacute/icircumflex/idieresis
  /eth/ntilde/ograve/oacute/ocircumflex/otilde
  /odieresis/divide/oslash/ugrave/uacute/ucircumflex
  /udieresis/yacute/thorn/ydieresis
] def

/SymbolEncoding [
  32/space/exclam/universal/numbersign/existential/percent
  /ampersand/suchthat/parenleft/parenright/asteriskmath/plus
  /comma/minus/period/slash/zero/one/two/three/four/five/six
  /seven/eight/nine/colon/semicolon/less/equal/greater/question
  /congruent/Alpha/Beta/Chi/Delta/Epsilon/Phi/Gamma/Eta/Iota
  /theta1/Kappa/Lambda/Mu/Nu/Omicron/Pi/Theta/Rho/Sigma/Tau
  /Upsilon/sigma1/Omega/Xi/Psi/Zeta/bracketleft/therefore
  /bracketright/perpendicular/underscore/radicalex/alpha
  /beta/chi/delta/epsilon/phi/gamma/eta/iota/phi1/kappa/lambda
  /mu/nu/omicron/pi/theta/rho/sigma/tau/upsilon/omega1/omega
  /xi/psi/zeta/braceleft/bar/braceright/similar
  161/Upsilon1/minute/lessequal/fraction/infinity/florin/club
  /diamond/heart/spade/arrowboth/arrowleft/arrowup/arrowright
  /arrowdown/degree/plusminus/second/greaterequal/multiply
  /proportional/partialdiff/bullet/divide/notequal/equivalence
  /approxequal/ellipsis/arrowvertex/arrowhorizex/carriagereturn
  /aleph/Ifraktur/Rfraktur/weierstrass/circlemultiply
  /circleplus/emptyset/intersection/union/propersuperset
  /reflexsuperset/notsubset/propersubset/reflexsubset/element
  /notelement/angle/gradient/registerserif/copyrightserif
  /trademarkserif/product/radical/dotmath/logicalnot/logicaland
  /logicalor/arrowdblboth/arrowdblleft/arrowdblup/arrowdblright
  /arrowdbldown/lozenge/angleleft/registersans/copyrightsans
  /trademarksans/summation/parenlefttp/parenleftex/parenleftbt
  /bracketlefttp/bracketleftex/bracketleftbt/bracelefttp
  /braceleftmid/braceleftbt/braceex
  241/angleright/integral/integraltp/integralex/integralbt
  /parenrighttp/parenrightex/parenrightbt/bracketrighttp
  /bracketrightex/bracketrightbt/bracerighttp/bracerightmid
  /bracerightbt
] def

/patarray [
/leftdiagonal /rightdiagonal /crossdiagonal /horizontal
/vertical /crosshatch /fishscale /wave /brick
] def
/arrowtype 0 def
/fillC 0 def /fillM 0 def /fillY 0 def /fillK 0 def
/strokeC 0 def /strokeM 0 def /strokeY 0 def /strokeK 1 def
/pattern -1 def
/mat matrix def
/mat2 matrix def
/nesting 0 def
/deferred /N def
/c /curveto load def
/c2 { pop pop c } bind def
/C /curveto load def
/C2 { pop pop C } bind def
/e { gsave concat 0 0 moveto } bind def
/F {
  nesting 0 eq { %ifelse
    pattern -1 eq { %ifelse
      fillC fillM fillY fillK setcmykcolor eofill
    }{ %else
      gsave fillC fillM fillY fillK setcmykcolor eofill grestore
      0 0 0 1 setcmykcolor
      patarray pattern get findfont patternfill
    } ifelse
  }{ %else
    /deferred /F def
  } ifelse
} bind def
/f { closepath F } bind def
/K { /strokeK exch def /strokeY exch def
     /strokeM exch def /strokeC exch def } bind def
/k { /fillK exch def /fillY exch def
     /fillM exch def /fillC exch def } bind def
/opc { pop } bind def
/Opc { pop } bind def
/L /lineto load def
/L2 { pop pop L } bind def
/m /moveto load def
/m2 { pop pop m } bind def
/n /newpath load def
/N {
  nesting 0 eq { %ifelse
    newpath
  }{ %else
    /deferred /N def
  } ifelse
} def
/S {
  nesting 0 eq { %ifelse
    strokeC strokeM strokeY strokeK setcmykcolor stroke
  }{ %else
    /deferred /S def
  } ifelse
} bind def
/s { closepath S } bind def
/Tx { fillC fillM fillY fillK setcmykcolor show
      0 leading neg translate 0 0 moveto } bind def
/T { grestore } bind def
/TX { pop } bind def
/Ts { pop } bind def
/tal { pop } bind def
/tld { pop } bind def
/tbx { pop exch pop sub /jwidth exch def } def
/tpt { %def
  fillC fillM fillY fillK setcmykcolor
  moveto show
} bind def
/tpj { %def
  fillC fillM fillY fillK setcmykcolor
  moveto
  dup stringwidth pop
  3 -1 roll
  exch sub
  1 index spacecount
  dup 0 eq { %ifelse
    pop pop show
  }{ %else
    div 0 8#040 4 -1 roll widthshow
  } ifelse
} bind def
/u {} def
/U {} def
/*u { /nesting nesting 1 add def } def
/*U {
  /nesting nesting 1 sub def
  nesting 0 eq {
    deferred cvx exec
  } if
} def
/w /setlinewidth load def
/d /setdash load def
/B {
  nesting 0 eq { %ifelse
    gsave F grestore S
  }{ %else
    /deferred /B def
  } ifelse
} bind def
/b { closepath B } bind def
/z { /align exch def pop /leading exch def exch findfont
     exch scalefont setfont } bind def
/tfn { exch findfont
     exch scalefont setfont } bind def
/Pat { /pattern exch def } bind def
/cm { 6 array astore concat } bind def
/q { mat2 currentmatrix pop } bind def
/Q { mat2 setmatrix } bind def
/Ah {
  pop /arrowtype exch def
  currentlinewidth 5 1 roll arrowhead
} bind def
/Arc {
  mat currentmatrix pop
    translate scale 0 0 1 5 -2 roll arc
  mat setmatrix
} bind def
/Arc2 { pop pop Arc } bind def
/Bx {
  mat currentmatrix pop
    concat /y1 exch def /x1 exch def /y2 exch def /x2 exch def
    x1 y1 moveto x1 y2 lineto x2 y2 lineto x2 y1 lineto
  mat setmatrix
} bind def
/Rr {
  mat currentmatrix pop
    concat /yrad exch def /xrad exch def
    2 copy gt { exch } if /x2 exch def /x1 exch def
    2 copy gt { exch } if /y2 exch def /y1 exch def
    x1 xrad add y2 moveto
    matrix currentmatrix x1 xrad add y2 yrad sub translate xrad yrad scale
    0 0 1 90 -180 arc setmatrix
    matrix currentmatrix x1 xrad add y1 yrad add translate xrad yrad scale
    0 0 1 180 270 arc setmatrix
    matrix currentmatrix x2 xrad sub y1 yrad add translate xrad yrad scale
    0 0 1 270 0 arc setmatrix
    matrix currentmatrix x2 xrad sub y2 yrad sub translate xrad yrad scale
    0 0 1 0 90 arc setmatrix
    closepath
  mat setmatrix
} bind def
/Ov {
  mat currentmatrix pop
    concat translate scale 1 0 moveto 0 0 1 0 360 arc closepath
  mat setmatrix
} bind def
end
%%EndResource
%%EndProlog
%%BeginSetup
%PDX g 3 3 0 0
%%IncludeFont: TimesNewRomanPSMT
PDXDict begin
%%EndSetup
%%Page: 1 1
%%BeginPageSetup
/_PDX_savepage save def

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/rightdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/leftdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  2 setlinewidth stroke
} bind
/horizontal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/vertical true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/crosshatch true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 30 7.5 lineto
  0 22.5 moveto 30 22.5 lineto
  7.5 0 moveto 7.5 7.5 lineto
  7.5 22.5 moveto 7.5 30 lineto
  22.5 7.5 moveto 22.5 22.5 lineto
  1 setlinewidth stroke
} bind
/brick true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  0.5 setlinewidth stroke
} bind
/crossdiagonal true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  1 setlinecap
  0 7.5 moveto 0 15 7.5 270 360 arc
  7.5 15 moveto 15 15 7.5 180 270 arc
  0 7.5 moveto 7.5 7.5 7.5 180 360 arc
  0.5 setlinewidth stroke
} bind
/fishscale true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  1 setlinecap 0.5 setlinewidth
  7.5 0 10.6 135 45 arcn
  22.5 15 10.6 225 315 arc
  stroke
  7.5 15 10.6 135 45 arcn
  22.5 30 10.6 225 315 arc
  stroke
} bind
/wave true definepattern pop

WinAnsiEncoding /_TimesNewRomanPSMT /TimesNewRomanPSMT RE

newpath 2 setlinecap 0 setlinejoin 2 setmiterlimit
[] 0 setdash
-7 675 moveto -7 794 lineto 192 794 lineto 192 675 lineto closepath clip
newpath
%%EndPageSetup
u
1 0.215686 1 0 K
1 w
q
0.07304 0.1812 -0.2054 -0.02154 259 776.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1953 0.0001234 -0.09647 -0.1825 185.8 883.5 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.08194 0.1212 -0.202 -0.1365 284.2 831.4 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.08194 0.1212 -0.202 -0.1365 283.2 831.3 cm
202.287 579 m
245.287 579 L
Q
S
U
[0.9998 0.02163 -0.02163 0.9998 59.7 126.6] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P25) 95.437 647.003 tpt
T
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
0.1832 0.06809 -0.1542 0.1373 237.6 613.1 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1317 -0.1443 -0.1999 -0.0516 267.7 739.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.03442 0.1422 -0.2369 0.05737 295.5 631.5 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.03442 0.1422 -0.2369 0.05737 294.8 632.2 cm
202.287 579 m
245.287 579 L
Q
S
U
[0.9998 0.02163 -0.02163 0.9998 85.44 47.29] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P26) 95.437 647.003 tpt
T
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
q
0.1294 -0.2138 0.2138 0.1294 22.85 679.5 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.2275 -0.1035 -0.1035 0.2275 235.2 614.2 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.2388 -0.07386 0.07386 0.2388 58.93 612.5 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.2388 -0.07386 0.07386 0.2388 59.95 613.1 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
0.1892 0.1198 -0.1916 0.1584 248 656.3 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1681 -0.1713 -0.2103 -0.1005 260.1 829.5 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.01408 0.1948 -0.2688 0.03876 308.3 690.4 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.01408 0.1948 -0.2688 0.03876 307.4 691.1 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 0.0588235 0 K
q
-0.1384 0.05854 0.01381 -0.1582 129.8 823.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.002495 0.1503 0.1391 -0.07666 46.25 768.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.09429 -0.06139 0.1023 -0.1571 87.61 843.4 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.09429 -0.06139 0.1023 -0.1571 87.66 842.6 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
q
0.1239 0.1575 -0.2084 0.03776 230.1 726.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1924 -0.05594 -0.1474 -0.152 189 852.9 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.04586 0.1428 -0.238 -0.07643 270.9 773.5 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.04586 0.1428 -0.238 -0.07643 269.9 773.6 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
0.04628 -0.1347 0.154 0.05111 60.88 697.8 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.1583 -0.03499 -0.02793 0.1397 182.7 638.8 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.1369 -0.06665 0.08433 0.1277 72.63 656.1 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.1369 -0.06665 0.08433 0.1277 73.35 656.4 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
q
-0.07445 -0.1473 0.1473 -0.07445 53.88 785.7 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.1375 0.0912 0.0912 0.1375 91.61 644 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.04213 -0.1595 0.1595 0.04213 29.08 742.1 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.04213 -0.1595 0.1595 0.04213 29.7 741.7 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
-0.1781 -0.09175 0.1738 -0.121 -52.75 821.3 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.1517 0.1309 0.1973 0.07695 -68.05 688.9 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.01768 -0.1489 0.2482 -0.02947 -109.5 795.2 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.01768 -0.1489 0.2482 -0.02947 -108.7 794.6 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 0.0588235 0 K
q
-0.02146 -0.09787 0.102 0.02837 -35.54 727.6 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.0988 -0.01672 0.03325 0.1005 10.57 679.5 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.05175 -0.0543 0.0905 0.08623 -43.62 697.4 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.05175 -0.0543 0.0905 0.08623 -43.12 697.5 cm
202.287 579 m
245.287 579 L
Q
S
U
1 1 1 0 K
0.5 w
61.6706 719.996 49.6847 734.006 [0.594 -0.8045 0.8045 0.594 -582.3 337.9] Bx
b
0.937255 0.937255 0.937255 0 k
119.737 714.846 100.23 725.313 [1 0 0 1 0 0] Bx
b
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
1 w
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
q
0.1103 -0.1673 0.1017 0.1858 -53.92 618.4 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.1139 -0.1649 -0.09762 0.1879 79.36 617.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.15 -0.001643 0.002738 0.25 -21.94 564.8 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.15 -0.001643 0.002738 0.25 -21.44 565.7 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
0.0792 -0.17 0.17 0.0792 -86.34 699.4 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.178 -0.05872 -0.05872 0.178 66.7 633.6 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.1721 -0.07444 0.07444 0.1721 -64.85 646.5 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.1721 -0.07444 0.07444 0.1721 -64.02 646.9 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 0.0588235 0 K
q
0.1439 0.04344 -0.1117 0.1129 85.32 637.4 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.09413 -0.1172 -0.156 -0.02994 114.6 733 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.03329 0.1075 -0.1791 0.0555 130.7 648.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.03329 0.1075 -0.1791 0.0555 130.2 649.5 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
-0.2333 0.1162 -0.1879 -0.1636 193.2 810.8 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.2139 0.1489 0.2097 -0.1345 -72.62 790.9 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.2992 -0.02193 0.01463 -0.1995 125.2 848.5 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.2992 -0.02193 0.01463 -0.1995 124.3 847.8 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
q
-0.1638 0.02016 -0.02016 -0.1638 80.83 832 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.03922 0.1603 0.1603 -0.03922 -39.65 748.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.1358 -0.0937 0.0937 -0.1358 31.36 840.6 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.1358 -0.0937 0.0937 -0.1358 31.25 839.8 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 0.0588235 0 K
q
-0.0552 0.1555 -0.1555 -0.0552 168.9 760.5 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1609 0.03659 0.03659 -0.1609 40.29 831 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.1445 0.07957 -0.07957 -0.1445 154.4 808.6 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.1445 0.07957 -0.07957 -0.1445 153.7 808.4 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
0.03926 0.1369 -0.1555 0.04639 175.1 713 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1498 -0.06209 -0.05719 -0.1305 109.1 831.2 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.074 0.1331 -0.1423 -0.05628 189.4 753.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.074 0.1331 -0.1423 -0.05628 188.7 754.1 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
q
0.1718 0.1031 -0.1813 0.1095 149.9 631.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1599 -0.1208 -0.1919 -0.08958 156.6 764.3 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
0.00799 0.1498 -0.2496 0.01332 204.9 660.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
0.00799 0.1498 -0.2496 0.01332 204 661.4 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
q
0.1135 0.07612 -0.1332 0.06485 144.4 659.5 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.119 -0.07332 -0.1283 -0.06799 140.8 748.3 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.00365 0.09998 -0.175 -0.002086 180.9 681.6 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.00365 0.09998 -0.175 -0.002086 180.3 682 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 0.0588235 0 K
q
0.1158 0.09587 -0.1468 0.06065 170.4 665.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1322 -0.07147 -0.1321 -0.08812 160.3 764.6 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.01103 0.112 -0.1866 -0.01835 207.8 693.3 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.01103 0.112 -0.1866 -0.01835 207.1 693.6 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 1 0 K
q
0.08475 0.1144 -0.1294 0.09795 178.1 638.6 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1185 -0.1107 -0.0993 -0.1022 157.7 772.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.02265 0.1506 -0.153 -0.002836 205.8 671.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.02265 0.1506 -0.153 -0.002836 205.2 672.3 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
q
0.134 0.149 -0.2054 0.0515 243.5 664.2 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1883 -0.06857 -0.1572 -0.1419 210.8 793.4 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.03629 0.1455 -0.2426 -0.06048 287.3 708.7 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.03629 0.1455 -0.2426 -0.06048 286.3 709 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
q
-0.2375 0.07794 -0.07794 -0.2375 200 855.7 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
0.1052 0.2267 0.2267 -0.1052 -3.596 766.9 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.2293 -0.09951 0.09951 -0.2293 129 883 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.2293 -0.09951 0.09951 -0.2293 128.6 881.9 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
q
-0.1781 -0.09175 0.1738 -0.121 15.8 819 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.1517 0.1309 0.1973 0.07695 0.5014 686.6 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.01768 -0.1489 0.2482 -0.02947 -40.95 792.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.01768 -0.1489 0.2482 -0.02947 -40.1 792.3 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
q
-0.1541 -0.164 0.164 -0.1541 -0.3858 847.4 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.1448 0.1722 0.1722 0.1448 -5.508 647.6 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.006242 -0.2249 0.2249 -0.006242 -49.72 799.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.006242 -0.2249 0.2249 -0.006242 -48.94 799.2 cm
202.287 579 m
245.287 579 L
Q
S
U
u
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 1 0.0588235 0 K
q
-0.127 -0.08031 0.1378 -0.0789 -6.695 798 cm
154.925 -141.194 95.1578 95.1578 176.938 645.162 Arc
Q
S
q
-0.122 0.08777 0.1423 0.07053 -9.384 698.1 cm
154.925 -140.194 94.8236 94.8236 176.938 645.162 Arc
Q
S
q
-0.00336 -0.1125 0.1874 -0.005627 -47.37 774.9 cm
9.24608 169.695 80.1644 80.1644 227.129 652.332 Arc
Q
S
1 1 1 0 k
q
-0.00336 -0.1125 0.1874 -0.005627 -46.71 774.5 cm
202.287 579 m
245.287 579 L
Q
S
U
0.937255 0.937255 0.937255 0 k
0.5 w
90.7147 764.326 40.2833 776.22 [0.9734 0.229 -0.229 0.9734 176.1 2.419] Bx
f
[0.9999 -0.01435 0.01435 0.9999 -91.76 52.55] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 0.0588235 0 k
/_TimesNewRomanPSMT 10 tfn
(P2) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -20.42 82.55] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P8) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -89.11 115.1] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P4) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -68.28 52.75] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P1) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -91.41 79.6] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P3) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -78.25 98.37] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 0.0588235 0 k
/_TimesNewRomanPSMT 10 tfn
(P5) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -57.96 96.85] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P6) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -54.28 76.88] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P7) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 28.91 74.83] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 0.0588235 0 k
/_TimesNewRomanPSMT 10 tfn
(P15) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -29.05 101] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P18) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -19.02 47.99] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P11) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -37.35 68.59] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P9) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 58.2 106.1] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P22) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 44.48 58.46] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P14) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -7.158 91.2] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P17) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -41.75 45.82] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P10) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -5.736 41.33] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P12) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 11.54 51.28] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P13) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 15 93.81] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P16) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -23.74 112.9] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P19) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 35.72 110.1] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P21) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 56.56 78.97] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P23) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -5.766 109] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P20) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 36.78 87.48] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P24) 95.437 647.003 tpt
T
%%PageTrailer
_PDX_savepage restore
%%Trailer
end
showpage
%%EOF
