This directory contains the snippets for UltiSnips.
https://github.com/sirver/ultisnips

Standing On The Shoulders of Giants
===================================

The snippets have been collected from various other project which I want to
express my gratitude for. My main source for inspiration where the following
two projects:

   TextMate: http://svn.textmate.org/trunk/Bundles/
   SnipMate: http://code.google.com/p/snipmate/

UltiSnips has seen contributions by many individuals. Those contributions have
been merged into this collection seamlessly and without further comments.

## Table of Contents

* [Custom UltiSnippets](#custom-ultisnippets)
   * [Ada Snippets](#ada-snippets)
   * [All Snippets](#all-snippets)
   * [Bib Snippets](#bib-snippets)
   * [Bindzone Snippets](#bindzone-snippets)
   * [Blade Snippets](#blade-snippets)
   * [Coffee-jasmine Snippets](#coffee-jasmine-snippets)
   * [Coffee-react Snippets](#coffee-react-snippets)
   * [Coffee Snippets](#coffee-snippets)
   * [Cpp Snippets](#cpp-snippets)
   * [Crystal Snippets](#crystal-snippets)
   * [C Snippets](#c-snippets)
   * [Cs Snippets](#cs-snippets)
      * [Classes and Structs](#classes-and-structs)
      * [Main](#main)
      * [Properties](#properties)
      * [Blocks](#blocks)
      * [Loops](#loops)
      * [Branching](#branching)
      * [Wrappers](#wrappers)
      * [Exception Handling](#exception-handling)
      * [Linq](#linq)
      * [Feedback and Debugging](#feedback-and-debugging)
      * [Methods](#methods)
      * [Constructor](#constructor)
      * [Comments](#comments)
   * [Css Snippets](#css-snippets)
      * [Basics](#basics)
      * [Colors](#colors)
      * [Selectors](#selectors)
      * [Pseudo-elements](#pseudo-elements)
      * [Other](#other)
   * [Cuda Snippets](#cuda-snippets)
   * [Django Snippets](#django-snippets)
   * [D Snippets](#d-snippets)
   * [Eelixir Snippets](#eelixir-snippets)
   * [Ejs Snippets](#ejs-snippets)
   * [Elm Snippets](#elm-snippets)
   * [Erlang Snippets](#erlang-snippets)
   * [Eruby Snippets](#eruby-snippets)
   * [Gitcommit Snippets](#gitcommit-snippets)
   * [Go Snippets](#go-snippets)
   * [Haskell Snippets](#haskell-snippets)
   * [Help Snippets](#help-snippets)
   * [Htmldjango Snippets](#htmldjango-snippets)
   * [Htmljinja Snippets](#htmljinja-snippets)
   * [Html_minimal Snippets](#html_minimal-snippets)
   * [Html Snippets](#html-snippets)
      * [Shortcuts](#shortcuts)
      * [HTML Tags](#html-tags)
   * [Javascript Angular Snippets](#javascript-angular-snippets)
   * [Javascript Ember Snippets](#javascript-ember-snippets)
   * [Javascript Jasmine Arrow Snippets](#javascript-jasmine-arrow-snippets)
   * [Javascript Jsdoc Snippets](#javascript-jsdoc-snippets)
   * [Javascript Node Snippets](#javascript-node-snippets)
   * [Javascript React Snippets](#javascript-react-snippets)
   * [Javascript Snippets](#javascript-snippets)
   * [Java Snippets](#java-snippets)
   * [Jinja2 Snippets](#jinja2-snippets)
   * [Json Snippets](#json-snippets)
   * [Julia Snippets](#julia-snippets)
   * [Ledger Snippets](#ledger-snippets)
   * [Lhaskell Snippets](#lhaskell-snippets)
   * [Lua Snippets](#lua-snippets)
   * [Mail Snippets](#mail-snippets)
   * [Mako Snippets](#mako-snippets)
   * [Markdown Snippets](#markdown-snippets)
      * [Sections and Paragraphs](#sections-and-paragraphs)
      * [Text Formatting](#text-formatting)
      * [Common Stuff](#common-stuff)
   * [Matlab Snippets](#matlab-snippets)
   * [Objc Snippets](#objc-snippets)
   * [Ocaml Snippets](#ocaml-snippets)
   * [Octave Snippets](#octave-snippets)
   * [Pandoc Snippets](#pandoc-snippets)
   * [Perl Snippets](#perl-snippets)
   * [Php laravel Snippets](#php-laravel-snippets)
   * [Php phpspec Snippets](#php-phpspec-snippets)
   * [Php symfony2 Snippets](#php-symfony2-snippets)
   * [Php Snippets](#php-snippets)
   * [Plaintex Snippets](#plaintex-snippets)
      * [Environments](#environments)
      * [Inline and Display Math](#inline-and-display-math)
      * [Snippets for fast typing](#snippets-for-fast-typing)
      * [Equality](#equality)
      * [Other math symbols](#other-math-symbols)
      * [Sub and Superscript](#sub-and-superscript)
      * [Fractions](#fractions)
      * [Over text type](#over-text-type)
      * [Sums and Products](#sums-and-products)
      * [Calculus](#calculus)
      * [Real Analysis](#real-analysis)
      * [Matrices and Vectors](#matrices-and-vectors)
      * [(), [], {}, and their bigger Counterparts](#---and-their-bigger-counterparts)
      * [TikZ](#tikz)
      * [Qed Qea](#qed-qea)
      * [Lessons](#lessons)
      * [Sections](#sections)
      * [Text Edit](#text-edit)
      * [Preamble](#preamble)
      * [Run code straight from the latex file, such as sympy, maybe eval or matplotlib](#run-code-straight-from-the-latex-file-such-as-sympy-maybe-eval-or-matplotlib)
      * [Chemistry](#chemistry)
      * [Other](#other-1)
   * [Plsql Snippets](#plsql-snippets)
   * [Proto Snippets](#proto-snippets)
   * [Puppet Snippets](#puppet-snippets)
   * [Python Snippets](#python-snippets)
   * [Rails Snippets](#rails-snippets)
   * [Rnoweb Snippets](#rnoweb-snippets)
   * [Robot Snippets](#robot-snippets)
   * [R Snippets](#r-snippets)
   * [Rst Snippets](#rst-snippets)
   * [Rust Snippets](#rust-snippets)
   * [Sh Snippets](#sh-snippets)
   * [Snippets Snippets](#snippets-snippets)
   * [Soy Snippets](#soy-snippets)
   * [Supercollider Snippets](#supercollider-snippets)
   * [Svelte Snippets](#svelte-snippets)
   * [Tcl Snippets](#tcl-snippets)
   * [Typescript react Snippets](#typescript-react-snippets)
   * [Typescript Snippets](#typescript-snippets)
   * [Vim Snippets](#vim-snippets)
   * [Vue Snippets](#vue-snippets)
   * [Xhtml Snippets](#xhtml-snippets)
   * [Xml Snippets](#xml-snippets)
   * [Zsh Snippets](#zsh-snippets)

## Ada Snippets

You can view the snippet [here](./ada.snippets)

* `wi`:           with
* `pac`:          package
* `pacb`:         package body
* `ent`:          entry ... when
* `task`:         task
* `taskb`:        task body
* `acc`:          accept
* `prot`:         protected type
* `prob`:         protected body
* `gen`:          generic type
* `ty`:           type
* `tyd`:          type with default value
* `subty`:        subtype
* `dec`:          declare block
* `decn`:         declare named block
* `ifex`:         if expression
* `casex`:        case expression
* `fora`:         for all
* `fors`:         for some
* `if`:           if
* `ife`:          if ... else
* `el`:           else
* `eif`:          elsif
* `wh`:           while
* `nwh`:          named while
* `for`:          for
* `fore`:         for each
* `nfor`:         named for
* `nfore`:        named for each
* `proc`:         procedure
* `procd`:        procedure declaration
* `fun`:          function
* `fune`:         expression function
* `fund`:         function declaration
* `ret`:          extended return
* `rec`:          record
* `case`:         case
* `whe`:          when
* `wheo`:         when others
* `lo`:           loop
* `nlo`:          named loop
* `ex`:           exit when
* `put`:          Ada.Text_IO.Put
* `putl`:         Ada.Text_IO.Put_Line
* `get`:          Ada.Text_IO.Get
* `getl`:         Ada.Text_IO.Get_Line
* `newline`:      Ada.Text_IO.New_Line

## All Snippets

You can view the snippet [here](./all.snippets)

* `box`:        A nice box with the current comment symbol
* `bbox`:       A nice box over the full width
* `fold`:       Insert a vim fold marker
* `foldc`:      Insert a vim fold close marker
* `foldp`:      Insert a vim fold marker pair
* `lorem`:      Lorem Ipsum (example: lorem3)
* `modeline`:   Vim modeline
* `date`:       YYYY-MM-DD
* `ddate`:      Month DD, YYYY
* `diso`:       ISO format datetime
* `time`:       hh:mm
* `datetime`:   YYYY-MM-DD hh:mm
* `todo`:       TODO comment
* `uuid`:       Random UUID

## Bib Snippets

You can view the snippet [here](./bib.snippets)

* `online`:   Online resource
* `article`:  Article reference
* `book`:     Book reference
* `inb`:      In Book reference

## Bindzone Snippets

You can view the snippet [here](./bindzone.snippets)

* `zone`: Bootstrap a new Bind zonefile
* `A`:    Insert A Record

## Blade Snippets

You can view the snippet [here](./bindzone.snippets).
NOTE: This is extended from the [html](./html.snippets) snippets.

* `break`:      @break
* `component`:  @component directive
* `each`:       @each directive
* `else`:       @else directive
* `eif`:        @else if directive
* `for`:        @for directive
* `foreach`:    @foreach directive
* `extends`:    @extends directive
* `if`:         @if directive
* `ife`:        @if @else structure
* `include`:    @include directive
* `includeIf`:  @includeIf directive
* `isset`:      @isset directive
* `inject`:     @inject directive
* `lang`:       @lang directive
* `php`:        @php directive
* `push`:       @push directive
* `section`:    @section directive
* `show`:       @show directive
* `slot`:       @slot directive
* `unless`:     @unless directive
* `verbatim`:   @verbatim directive
* `wh`:         @while directive
* `yield`:      @yield directive
* `{`:          {{ }} statement.
* `{!`:         {!! !!} statement

## Coffee-jasmine Snippets

You can view the snippet [here](./coffee-jasmine.snippets).
NOTE: This extends from the [coffe](./coffee.snippets) snippets.

* `des`:        Describe
* `it`:         it
* `bef`:        before each
* `aft`:        after each
* `any`:        any
* `ru`:         runs
* `wa`:         waits
* `ex`:         expect
* `ee`:         expect to equal
* `em`:         expect to match
* `eha`:        expect to have attribute
* `et`:         expect to be truthy
* `ef`:         expect to be falsy
* `ed`:         expect to be defined
* `en`:         expect to be null
* `ec`:         expect to contain
* `ev`:         expect to be visible
* `eh`:         expect to be hidden
* `notx`:       expect not
* `note`:       expect not to equal
* `notm`:       expect not to match
* `notha`:      expect to not have attribute
* `nott`:       expect not to be truthy
* `notf`:       expect not to be falsy
* `notd`:       expect not to be defined
* `notn`:       expect not to be null
* `notc`:       expect not to contain
* `notv`:       expect not to be visible
* `noth`:       expect not to be hidden
* `s`:          spy on
* `sr`:         spy on and return
* `st`:         spy on and throw
* `sct`:        spy on and call through
* `scf`:        spy on and call fake
* `esc`:        expect was called
* `escw`:       expect was called with
* `notsc`:      expect was not called
* `noscw`:      expect was not called with

## Coffee-react Snippets

You can view the snippet [here](./coffee-react.snippets).
NOTE: This extends from the [coffe](./coffee.snippets) snippets.

* `createClass`:                React define Class
* `PropTypes`:                  React define propTypes
* `propType`:                   React propType (key/value)
* `setState`:                   React setState
* `getInitialState`:            React define getInitialState
* `getDefaultProps`:            React define getDefaultProps
* `componentWillMount`:         React define componentWillMount
* `componentDidMount`:          React define componentDidMount
* `componentWillReceiveProps`:  React define componentWillReceiveProps
* `shouldComponentUpdate`:      React define shouldComponentUpdate
* `componentWillUpdate`:        React define componentWillUpdate
* `componentDidUpdate`:         React define componentDidUpdate
* `componentWillUnmount`:       React define componentWillUnmount

## Coffee Snippets

You can view the snippet [here](./coffee.snippets).

* `fun`:    Function
* `bfun`:   Function (bound)
* `if`:     If
* `ife`:    If .. Else
* `elif`:   Else if
* `ifte`:   Ternary if
* `unl`:    Unless
* `fora`:   Array Comprehension
* `foro`:   Object Comprehension
* `forr`:   Range Comprehension (inclusive)
* `forrex`: Range Comprehension (exclusive)
* `swi`:    Switch
* `swit`:   Switch when .. then
* `cla`:    Class
* `try`:    Try .. Catch
* `req`:    Require
* `#`:      Interpolated Code
* `log`:    Log
* `kv`:     Key:value for object

## Cpp Snippets

You can view the snippet [here](./cpp.snippets).

* `main`:                 Main function
* `forc`:                 general for loop (for)
* `beginend`:             $1.begin(), $1.end() (beginend)
* `ns`:                   namespace .. (namespace)
* `readfile`:             read file (readF)
* `map`:                  std::map (m
* `vector`:               std::vector
* `tp`:                   template <typename ...> (template)
* `cla`:                  An entire .h genera
* `fnc`:                  Basic c++ doxygen function template
* `boost_test`:           Boost test mod
* `boost_suite`:          Boost test suite mod
* `boost_test_fixture`:   Boost test module with fixture
* `boost_suite_fixture`:  Boost test suite with fixture

## Crystal Snippets

You can view the snippet [here](./crystal.snippets).

* `"\b(de)?f"`:   def <name>...
* `"\b(pde)?f"`:  private def <name>...

## C Snippets

You can view the snippet [here](./c.snippets).

* `def`:        #define ...
* `#ifndef`:    #ifndef ... #define ... #endif
* `#if`:        #if #endif
* `mark`:       #pragma mark (mark)
* `main`:       main() (main)
* `for`:        for loop (for)
* `fori`:       for int loop (fori)
* `fora`:       for-loop
* `once`:       Include header once only guard
* `fprintf`:    fprintf ...
* `fun`:        function
* `fund`:       function declaration
* `head`:       File Header
* `func`:       Function Header

## Cs Snippets

You can view the snippet [here](./cs.snippets).

### Classes and Structs

* `namespace`: namespace
* `class`: class
* `struct`: struct
* `interface`: interface
* `enum`: enumeration

### Main

* `sim`: static int main
* `svm`: static void main

### Properties

* `prop`: Simple property declaration
* `propfull`: Full property declaration
* `propg`: Property with a private setter

### Blocks

* `#if`: #if #endif
* `#region`: #region #endregion

### Loops

* `for`: for loop
* `forr`: for loop (reverse)
* `foreach`: foreach loop
* `while`: while loop
* `do`: do loop

### Branching

* `if`: if statement
* `ife`: if else statement
* `elif`: else if
* `elseif`: else if
* `ifnn`: if not null
* `switch`: switch statement
* `case`: case

### Wrappers

* `using`: using statement
* `unchecked`: unchecked block
* `checked`: checked block
* `unsafe`: unsafe

### Exception Handling

* `try`: try catch block
* `tryf`: try finally block
* `throw`: throw

### Linq

* `from`: LINQ syntax

### Feedback and Debugging

* `da`: Debug.Assert
* `cw`: Console.WriteLine
* `cr`: Console.ReadLine
* `cwp`: Console.WriteLine with parameters
* `mbox`: Message box

### Methods

* `equals`: Equality for a type
* `mth`: Method
* `mths`: Static method

### Constructor

* `ctor`: Constructor

### Comments

* `///`: XML summary comment
* `<p`: XML pramameter comment
* `<ex`: XML exception comment
* `<r`: XML returns comment
* `<c`: XML code comment

## Css Snippets

You can view the snippet [here](./css.snippets).

### Basics

* `p`: padding
* `m`: margin
* `bd`: border
* `d`: display
* `bg`: background
* `ff`: font-family
* `h`: height
* `w`: width
* `pos`: position
* `tt`: text-transform
* `!`: !important CSS (!)
* `tsh`: text-shadow: color-hex x y blur (text)
* `bxsh`: box-shadow: color-hex x y blur (text)

### Colors

* `rgb`: color rgb
* `rgba`: color rgba
* `hsl`: color hsl
* `hsla`: color hsla

### Selectors

* `:fc`: First child
* `:lc`: Last child
* `:nc`: Nth child (0)
* `:nlc`: Nth last child
* `:oc`: Only child

### Pseudo-elements

* `:a`: :After
* `:b`: :Before
* `::a`: ::After
* `::b`: ::Before

### Other

* `background`: background-attachment: scroll:fixed (background)
* `background`: background-color:  color-hex (background)
* `background`: background-color:  color-name (background)
* `background`: background-color:  color-rgb (background)
* `background`: background-color:  transparent (background)
* `background`: background-image:  none (background)
* `background`: background-image:  url (background)
* `background`: background-position:  position (background)
* `background`: background-repeat:  r:r-x:r-y:n-r (background)
* `background`: background:  color image repeat attachment position (background)
* `border`: border-bottom-color: size style color (border)
* `border`: border-bottom-style: size style color (border)
* `border`: border-bottom-width: size style color (border)
* `border`: border-bottom: size style color (border)
* `border`: border-color: color (border)
* `border`: border-left-color: color (border)
* `border`: border-left-style: style (border)
* `border`: border-left-width: size (border)
* `border`: border-left: size style color (border)
* `border`: border-right-color: color (border)
* `border`: border-right-style: style (border)
* `border`: border-right-width: size (border)
* `border`: border-right: size style color (border)
* `border`: border-style: style (border)
* `border`: border-top-color: color (border)
* `border`: border-top-style: style (border)
* `border`: border-top-width: size (border)
* `border`: border-top: size style color (border)
* `border`: border-width: width (border)
* `border`: border:   size style color (border)
* `clear`: clear: value (clear)
* `color`: color:  color-hex (color)
* `color`: color:  color-name (color)
* `color`: color:  color-rgb (color)
* `cursor`: cursor: type (cursor)
* `cursor`: cursor: url (cursor)
* `direction`: direction: ltr|rtl (direction)
* `display`: display: block (display)
* `display`: display: common-types (display)
* `display`: display: inline (display)
* `display`: display: table-types (display)
* `float`: float: left:right:none (float)
* `font`: font-family:   family (font)
* `font`: font-size: size (font)
* `font`: font-style:   normal:italic:oblique (font)
* `font`: font-variant:   normal:small-caps (font)
* `font`: font-weight: weight (font)
* `font`: font:   style variant weight size:line-height font -family (font)
* `font`: font: size font (font)
* `letter`: letter-spacing:   length-em (letter)
* `letter`: letter-spacing:   length-px (letter)
* `list`: list-style-image: url (list)
* `list`: list-style-position: pos (list)
* `list`: list-style-type: asian (list)
* `list`: list-style-type: marker(list)
* `list`: list-style-type: numeric (list)
* `list`: list-style-type: other (list)
* `list`: list-style-type: roman-alpha-greek (list)
* `list`: list-style: type position image (list)
* `margin`: margin-bottom: length (margin)
* `margin`: margin-left: length (margin)
* `margin`: margin-right: length (margin)
* `margin`: margin-top: length (margin)
* `margin`: margin:   all (margin)
* `margin`: margin: T R B L (margin)
* `margin`: margin: V H (margin)
* `marker`: marker-offset: auto (marker)
* `marker`: marker-offset: length (marker)
* `overflow`: overflow: type (overflow)
* `padding`: padding-bottom: length (margin)
* `padding`: padding-left: length (margin)
* `padding`: padding-right: length (margin)
* `padding`: padding-top: length (margin)
* `padding`: padding:   T R B L (padding)
* `padding`: padding:   V H (padding)
* `padding`: padding:   all (padding)
* `position`: position: type (position)
* `{`: properties { } ( } )
* `scrollbar`: scrollbar
* `selection`: selection
* `text`: text-align: left:center:right (txt)
* `text`: text-decoration: none:underline:overline:line-through:blink (text)
* `text`: text-indent: length (text)
* `text`: text-transform: capitalize:upper:lower (text)
* `vertical`: vertical-align: type (vertical)
* `visibility`: visibility: type (visibility)
* `white`: white-space:  normal:pre:nowrap (white)
* `word`: word-spacing:  length (word)
* `z`: z-index: index (z)

## Cuda Snippets

You can view the snippet [here](./cuda.snippets).
View the [cpp](#cpp-snippets) section

## Django Snippets

You can view the snippet [here](./django.snippets).

* `form`: Form
* `modelform`: ModelForm
* `fbool`: BooleanField
* `fchar`: CharField
* `fchoice`: ChoiceField
* `fcombo`: ComboField
* `fdate`: DateField
* `fdatetime`: DateTimeField
* `fdecimal`: DecimalField
* `fmail`: EmailField
* `ffile`: FileField
* `ffilepath`: FilePathField
* `ffloat`: FloatField
* `fip`: IPAddressField
* `fimg`: ImageField
* `fint`: IntegerField
* `fmochoice`: ModelChoiceField
* `fmomuchoice`: ModelMultipleChoiceField
* `fmuval`: MultiValueField
* `fmuchoice`: MultipleChoiceField
* `fnullbool`: NullBooleanField
* `freg`: RegexField
* `fslug`: SlugField
* `fsdatetime`: SplitDateTimeField
* `ftime`: TimeField
* `ftchoice`: TypedChoiceField
* `ftmuchoice`: TypedMultipleChoiceField
* `furl`: URLField
* `model`: Model
* `modelfull`: Model
* `mauto`: AutoField
* `mbigint`: BigIntegerField
* `mbool`: BooleanField
* `mchar`: CharField
* `mcoseint`: CommaSeparatedIntegerField
* `mdate`: DateField
* `mdatetime`: DateTimeField
* `mdecimal`: DecimalField
* `memail`: EmailField
* `mfile`: FileField
* `mfilepath`: FilePathField
* `mfloat`: FloatField
* `fk`: ForeignKey
* `mip`: IPAddressField
* `mimg`: ImageField
* `mint`: IntegerField
* `m2m`: ManyToManyField
* `mnullbool`: NullBooleanField
* `o2o`: OneToOneField
* `mphone`: PhoneNumberField
* `mposint`: PositiveIntegerField
* `mpossmallint`: PositiveSmallIntegerField
* `mslug`: SlugField
* `msmallint`: SmallIntegerField
* `mtext`: TextField
* `mtime`: TimeField
* `murl`: URLField
* `musstate`: USStateField
* `mxml`: XMLField
* `adminview`: Model Admin View
* `createview`: Generic Create View
* `deleteview`: Generic Delete View
* `detailview`: Generic Detail View
* `listview`: Generic List View
* `stackedinline`: Stacked Inline
* `tabularinline`: Tabular Inline
* `templateview`: Generic Template View
* `updateview`: Generic Update View
* `dispatch`: Dispatch View method
* `context`: get_context_data view method

## D Snippets

You can view the snippet [here](./d.snippets).

* `imp`: import (imp)
* `pimp`: public import (pimp)
* `over`: override (over)
* `al`: alias (al)
* `mixin`: mixin (mixin)
* `new`: new (new)
* `scpn`: @safe const pure nothrow (scpn)
* `spn`: @safe pure nothrow (spn)
* `cont`: continue (cont)
* `dis`: @disable (dis)
* `pub`: public (pub)
* `priv`: private (priv)
* `prot`: protected (prot)
* `pack`: package (pack)
* `ret`: return (ret)
* `auto`: auto (auto)
* `con`: const (con)
* `siz`: size_t (siz)
* `sup`: super (sup)
* `tup`: tuple (tup)
* `wr`: writeln (wr)
* `to`: to (to)
* `enf`: enforce (enf)
* `if`: if .. (if)
* `ife`: if .. else (ife)
* `el`: else (el)
* `elif`: else if (elif)
* `sw`: switch (sw)
* `fsw`: final switch (fsw)
* `case`: case (case)
* `?:`: ternary operator (?:)
* `do`: do while (do)
* `wh`: while (wh)
* `for`: for (for)
* `forever`: forever (forever)
* `fore`: foreach (fore)
* `forif`: foreach if (forif)
* `in`: in contract (in)
* `out`: out contract (out)
* `inv`: invariant (inv)
* `fun`: function definition (fun)
* `void`: void function definition (void)
* `this`: ctor (this)
* `get`: getter property (get)
* `set`: setter property (set)
* `main`: Main
* `signal`: signal (signal)
* `scope`: scope (scope)
* `with`: with (with)
* `try`: try/catch (try)
* `tryf`: try/catch/finally (tryf)
* `catch`: catch (catch)
* `thr`: throw (thr)
* `struct`: struct (struct)
* `union`: union (union)
* `class`: class (class)
* `inter`: interface (inter)
* `enum`: enum (enum)
* `exc`: exception declaration (exc)
* `version`: version (version)
* `debug`: debug
* `temp`: template (temp)
* `ass`: assert (ass)
* `unittest`: unittest (unittest)
* `opDis`: opDispatch (opDis)
* `op=`: opAssign (op=)
* `opCmp`: opCmp (opCmp)
* `opApply`: opApply (opApply)
* `toString`: toString (toString)
* `todo`: TODO (todo)
* `doc`: generic ddoc block (doc)
* `fdoc`: function ddoc block (fdoc)
* `Par`: Params (Par)
* `Ret`: Returns (Ret)
* `Thr`: Throws (Thr)
* `Example`: Examples (Example)
* `gpl`: GPL (gpl)
* `boost`: Boost (boost)
* `module`: New module (module)

## Eelixir Snippets

You can view the snippet [here](./eelixir.snippets).
NOTE: This is extended from the [html](./html.snippets) snippets.

* `%`: <% %>
* `=`: <%= %>
* `end`: <% end %>
* `for`: for loop
* `ft`: form_tag
* `lin`: link
* `ff`: form_for
* `gt`: gettext

## Ejs Snippets

You can view the snippet [here](./ejs.snippets).

* `for`: ejs for loop
* `forE`: ejs for Each loop

## Elm Snippets

You can view the snippet [here](./ejs.snippets).

* `impa`: "Qualified import
* `impae`: "Qualified import with exposing

## Erlang Snippets

You can view the snippet [here](./ejs.snippets).

* `pat`: Case:Receive:Try Clause
* `mod`: Module Directive
* `||`: List Comprehension
* `gen`: Generator Expression

## Eruby Snippets

You can view the snippet [here](./eruby.snippets).

* `%`: <% $0 %>
* `=`: <%= $0 %>
* `fi`: <%= Fixtures.identify(:symbol) 
* `ft`: form_tag
* `ffs`: form_for submit 2
* `f.`: f_fields_for (nff)
* `f.`: f.checkbox
* `f.`: f.file_field
* `f.`: f.hidden_field
* `f.`: f.label
* `f.`: f.password_field
* `f.`: f.radio_button
* `f.`: f.submit
* `f.`: f.text_area
* `f.`: f.text_field
* `ffe`: form_for with errors
* `ff`: form_for
* `ist`: image_submit_tag
* `it`: image_tag
* `layout`: layout
* `jit`: javascript_include_tag
* `lt`: link_to (name, dest)
* `lia`: link_to (action)
* `liai`: link_to (action, id)
* `lic`: link_to (controller)
* `lica`: link_to (controller, action)
* `licai`: link_to (controller, action, id)
* `linpp`: link_to (nested path plural)
* `linp`: link_to (nested path)
* `lipp`: link_to (path plural)
* `lip`: link_to (path)
* `lim`: link_to model
* `hide`: page.hide (*ids)
* `ins`: page.insert_html (position, id, partial)
* `rep`: page.replace (id, partial)
* `reph`: page.replace_html (id, partial)
* `show`: page.show (*ids)
* `tog`: page.toggle (*ids)
* `vis`: page.visual_effect (effect, id)
* `rp`: render (partial) (rp)
* `rpc`: render (partial,collection) (rpc)
* `rpl`: render (partial,locals) (rpl)
* `rpo`: render (partial,object) (rpo)
* `rps`: render (partial,status) (rps)
* `slt`: stylesheet_link_tag
* `st`: submit_tag
* `else`: else (ERB)
* `lf`: link_to_function

## Gitcommit Snippets

You can view the snippet [here](./gitcommit.snippets).

* `status`: Status
* `fix`: fix conventional commit
* `feat`: feat conventional commit
* `chore`: chore conventional commit
* `docs`: docs conventional commit
* `improvement`: improvement conventional commit
* `perf`: perf conventional commit
* `refactor`: refactor conventional commit
* `test`: test conventional commit
* `ci`: ci conventional commit
* `build`: build conventional commit
* `sign`: Signature
* `t`: Todo
* `cmt`: Commit Structure

## Go Snippets

You can view the snippet [here](./go.snippets).

* `/^import/`: Import declaration
* `/^package/`: Package declaration
* `/^cons/`: Constants declaration
* `/^con/`: Constant declaration
* `iota`: Iota constant generator
* `struct`: Struct declaration
* `interface`: Interface declaration
* `if`: If statement
* `switch`: Switch statement
* `/^main/`: Main function
* `/^meth/`: Method
* `func`: Function
* `funch`: HTTP handler
* `map`: Map type
* `:`: Variable declaration :=
* `var`: Variable declaration
* `vars`: Variables declaration
* `json`: JSON field
* `err`: Basic error handling

## Haskell Snippets

You can view the snippet [here](./haskell.snippets).

* `imp`: Simple import
* `imp2`: Selective import
* `impq`: Qualified import

## Help Snippets

You can view the snippet [here](./help.snippets).

* `sec`: Section marker
* `ssec`: Sub section marker
* `sssec`: Subsub Section marker
* `modeline`: Vim help modeline

## Htmldjango Snippets

You can view the snippet [here](./htmldjango.snippets).
NOTE: This is extended from the [html](./html.snippets) snippets.

* `%`:
* `%%`:
* `{`:
* `autoescape`:
* `block`:
* `#`:
* `comment`:
* `cycle`:
* `debug`:
* `extends`:
* `filter`:
* `firstof`:
* `for`:
* `empty`:
* `if`:
* `iif`:
* `ielse`:
* `else`:
* `ielif`:
* `elif`:
* `ifchanged`:
* `ifequal`:
* `ifnotequal`:
* `include`:
* `load`:
* `now`:
* `regroup`:
* `spaceless`:
* `ssi`:
* `trans`:
* `url`:
* `widthratio`:
* `with`:
* `verbatim`:
* `super`:
* `staticu`:
* `static`:
* `mediau`:
* `iblock`:
* `csrf`:
* `blocktrans`:
* `lorem`:
* `add`:
* `center`:
* `cut`:
* `date`:
* `default`:
* `defaultifnone`:
* `dictsort`:
* `dictsortrev`:
* `divisibleby`:
* `floatformat`:
* `getdigit`:
* `join`:
* `lengthis`:
* `pluralize`:
* `removetags`:
* `slice`:
* `stringformat`:
* `time`:
* `truncatewords`:
* `truncatewordshtml`:
* `urlizetrunc`:
* `wordwrap`:

## Htmljinja Snippets

You can view the snippet [here](./htmljinja.snippets).
NOTE: This is extended from the [html](./html.snippets) snippets.
NOTE: This is extended from the [html](./jinja2.snippets) snippets.

## Html_minimal Snippets

You can view the snippet [here](./html_minimal.snippets).

* `id`: Create an id
* `idn`: Create an id and name
* `label_and_input`: Create a label and an input tag
* `input`: Create an input tag
* `submit`: Create a submit tag
* `textarea`: Create a textarea tag
* `img`: Create an image tag

## Html Snippets

You can view the snippet [here](./html.snippets).

### Shortcuts

* `down`: Down
* `enter`: Enter
* `escape`: Escape
* `left`: Left
* `return`: Return
* `right`: Right
* `shift`: Shift
* `tab`: Tab
* `up`: Up

### HTML Tags

* `a`: Link
* `abbr`: \<abbr\>
* `access`: accesskey global attribute
* `address`: \<address\>
* `article`: \<article\>
* `aside`: \<aside\>
* `b`: \<b\>
* `base`: HTML \<base\>
* `blockquote`: \<blockquote\>
* `body`: \<body\>
* `br`: \<br\>
* `button`: \<button\>
* `caption`: \<caption\>
* `cite`: \<cite\>
* `class`: class global attribute
* `code`: \<code\>
* `data`: \<data\>
* `datalist`: \<datalist\>
* `dd`: \<dd\>
* `del`: \<del\>
* `dfn`: \<dfn\>
* `div`: \<div\>
* `div#`: \<div\> with ID & class
* `div.`: \<div\> with class
* `dl`: \<dl\>
* `dt`: \<dt\>
* `em`: \<em\>
* `fieldset`: Fieldset
* `fig`: \<figure\>
* `figcaption`: \<figcaption\>
* `footer`: \<footer\>
* `form`: HTML \<form\>
* `h1`: HTML \<h1\>
* `h2`: HTML \<h2\>
* `h3`: HTML \<h3\>
* `h4`: HTML \<h4\>
* `h5`: HTML \<h5\>
* `h6`: HTML \<h6\>
* `head`: HTML \<head\>
* `header`: \<header\>
* `hr`: \<hr\>
* `html`: HTML basic structure
* `htmll`: HTML basic structure with the lang attribute
* `i`: \<i\>
* `id`: id global attribute
* `img`: \<img\>
* `input`: Input with Label
* `input`: HTML \<input\>
* `ins`: \<ins\>
* `kbd`: \<kbd\>
* `label`: \<label\>
* `legend`: \<legend\>
* `li`: list item
* `link`: HTML \<link\>
* `mailto`: HTML \<a mailto: \>
* `tel`: HTML \<a tel: \>
* `main`: \<main\>
* `mark`: \<mark\>
* `meta`: HTML \<meta\>
* `meter`: \<meter\>
* `nav`: \<nav\>
* `noscript`: \<noscript\>
* `ol`: \<ol\>
* `optgroup`: \<optgroup\>
* `output`: \<output\>
* `option`: Option
* `p`: paragraph
* `picture`: \<picture\>
* `pre`: \<pre\>
* `progress`: \<progress\>
* `q`: \<q\>
* `s`: \<s\>
* `samp`: \<samp\>
* `script`: HTML \<script\>
* `scriptsrc`: HTML \<script src...\>
* `select`: Select Box
* `small`: \<small\>
* `span`: \<span\>
* `span#`: \<span\> with ID & class
* `span.`: \<span\> with class
* `strong`: \<strong\>
* `style`: HTML \<style\>
* `sub`: \<sub\>
* `sup`: \<sup\>
* `table`: HTML \<table\>
* `tbody`: \<tbody\>
* `td`: table cell
* `template`: \<template\>
* `textarea`: HTML \<textarea\>
* `tfoot`: \<tfoot\>
* `th`: table header
* `thead`: \<thead\>
* `time`: \<time\>
* `title`: HTML \<title\>
* `tr`: table row
* `ul`: unordered list
* `var`: \<var\>
* `viewport`: Responsive viewport meta
* `wbr`: \<wbr\>

## Javascript Angular Snippets

You can view the snippet [here](./javascript-angular.snippets).

* `iti`: it (js, inject)
* `befi`: before each (js, inject)
* `aconf`: angular config
* `acont`: angular controller
* `aconts`: angular controller with scope
* `adir`: angular directive
* `adirs`: angular directive with scope
* `afact`: angular factory
* `afacts`: angular factory with scope
* `aserv`: angular service
* `aservs`: angular service

## Javascript Ember Snippets

You can view the snippet [here](./javascript-ember.snippets).

* `eapp`: App.Name = Ember.Application.create({});
* `emod`: import DS from 'ember-data';
* `econtroller`: import Controller from '@ember/controller';
* `eroute`: import Route from '@ember/routing/route';
* `ecomponent`: import Component from '@ember/component';
* `eobj`: import EmberObject from '@ember/object';
* `emix`: App.MixinName = Ember.Model.extend({...});
* `eget`: this.get('property');
* `cproimport`: import { computed } from '@ember/object';
* `prooimport`: import { observer } from '@ember/object';
* `proo`: property_name: observer('...', function() {...}),

## Javascript Jasmine Arrow Snippets

You can view the snippet [here](./javascript-jasmine-arrow.snippets).

* `des`: Describe 
* `it`: it
* `bef`: before each
* `aft`: after each
* `befa`: before all
* `afta`: after all
* `ru`: runs

## Javascript Jsdoc Snippets

You can view the snippet [here](./javascript-jsdoc.snippets).

* `/`: A JSDoc comment
* `@au`: @author email (First Last)
* `@li`: @license Description
* `@ver`: @version Semantic version
* `@fileo`: @fileoverview Description
* `@constr`: @constructor
* `@p`: @param {Type} varname Description
* `@ret`: @return {Type} Description
* `@pri`: @private
* `@over`: @override
* `@pro`: @protected

## Javascript Node Snippets

You can view the snippet [here](./javascript-node.snippets).

* `#!`: #!/usr/bin/env node
* `vreq`: assign a CommonJS-style module to a var
* `ex`: module.exports
* `hcs`: http.createServer
* `ncs`: net.createServer
* `pipe`: pipe
* `eget`: express GET
* `epost`: express POST
* `eput`: express PUT
* `edelete`: express DELETE
* `stdout`: stdout
* `stdin`: stdin
* `stderr`: stderr

## Javascript React Snippets

You can view the snippet [here](./javascript-react.snippets).

* `rfc`: react functional component
* `useS`: useState Hook
* `useRe`: useReducer Hook
* `useCB`: useCallback(fn, inputs)
* `useM`: useMemo(fn, inputs)
* `useR`: useRef(defaultValue)
* `ir`: import React
* `irc`: import React and Component

## Javascript Snippets

You can view the snippet [here](./javascript.snippets).

* `get`: Get Elements
* `'':f`: object method string
* `:f`: Object Method
* `:,`: Object Value JS
* `:`: Object key key: 'value'
* `proto`: Prototype (proto)
* `fun`: function (named)
* `vf`: function (assigned to var)
* `fun`: function (anonymous)
* `anf`: function (anonymous)
* `iife`: Immediately-Invoked Function Expression (iife)
* `;fe`: Minify safe iife
* `timeout`: setTimeout function
* `fi`: for prop in obj using hasOwnProperty
* `if`: if (condition) { ... }
* `ife`: if (condition) { ... } else { ... }
* `switch`: switch
* `case`: case 'xyz': ... break
* `do`: do { ... } while (condition)
* `ret`: Return statement
* `imp`: import
* `cl`: console.log
* `cd`: console.debug
* `ce`: console.error
* `cw`: console.warn
* `ci`: console.info
* `ct`: console.trace
* `ctime`: console.time ... console.timeEnd
* `ctimestamp`: console.timeStamp
* `ca`: console.assert
* `cclear`: console.clear
* `cdir`: console.dir
* `cdirx`: console.dirxml
* `cgroup`: console.group
* `cgroupc`: console.groupCollapsed
* `cprof`: console.profile
* `ctable`: console.table
* `clstr`: console.log stringified

## Java Snippets

You can view the snippet [here](./java.snippets).

* `sleep`: try sleep catch
* `/i|n/`: new primitive or int
* `/o|v/`: new Object or variable
* `f`: field
* `ab`: abstract
* `as`: assert
* `at`: assert true
* `af`: assert false
* `ae`: assert equals
* `br`: break
* `cs`: case
* `ca`: catch
* `cle`: class extends
* `clc`: class with constructor, fields, setter and getters
* `clc`: class with constructor, with field names
* `clc`: class and constructor
* `cl`: class
* `cos`: constant string
* `co`: constant
* `de`: default
* `elif`: else if
* `el`: else
* `fi`: final
* `fore`: for (each)
* `fori`: for
* `for`: for
* `if`: if
* `imt`: import junit_framework_TestCase;
* `im`: import
* `in`: interface
* `cc`: constructor call or setter body
* `list`: Collections List
* `map`: Collections Map
* `set`: Collections Set
* `/Str?|str/`: String
* `cn`: Constructor
* `cn`: constructor, \w fields + assigments
* `j.b`: java_beans_
* `j.i`: java_io
* `j.m`: java_math
* `j.n`: java_net_
* `j.u`: java_util_
* `main`: method (main)
* `try`: try/catch
* `mt`: method throws
* `m`: method
* `md`: Method With javadoc
* `/get(ter)?/`: getter
* `/set(ter)?/`: setter
* `/se?tge?t|ge?tse?t|gs/`: setter and getter
* `pa`: package
* `p`: print
* `pl`: println
* `pr`: private
* `po`: protected
* `pu`: public
* `re`: return
* `st`: static
* `sw`: switch
* `sy`: synchronized
* `tc`: test case
* `t`: test
* `tt`: test throws
* `th`: throw
* `wh`: while

## Jinja2 Snippets

You can view the snippet [here](./jinja2.snippets).

* `block`: block
* `{{`: variable
* `{#`: comment
* `#`: comment
* `raw`: escaped block
* `extends`: extends
* `include`: include
* `import`: import
* `from`: from/import/as
* `filter`: filter
* `for`: for
* `for`: for/else
* `if`: if
* `if`: if/else
* `if`: if/elif/else
* `macro`: macro
* `call`: call
* `set`: set
* `trans`: translation
* `with`: with
* `autoescape`: autoescape
* `batch`: batch items
* `dictsort`: sort and yield (key, value) pairs
* `round`: round number
* `urlize`: convert plain-text url to \<a/>
* `wordwrap`: wordwrap
* `truncate`: truncate
* `sum`: sum of sequence of numbers + start
* `sort`: sort an iterable
* `indent`: indent

## Json Snippets

You can view the snippet [here](./json.snippets).

* `s`: String
* `n`: Number
* `a`: Array
* `na`: Named array
* `o`: Object
* `no`: Named object
* `null`: Null
* `b`: Bool

## Julia Snippets

You can view the snippet [here](./julia.snippets).

* `docf`: function documentation
* `doct`: type definition
* `par`: function parameter documentation
* `fld`: type field documentation
* `deb`: Debugger breakpoint
* `inf`: Infiltrator breakpoint

## Ledger Snippets

You can view the snippet [here](./ledger.snippets).

* `t`: Transaction

## Lhaskell Snippets

You can view the snippet [here](./lhaskell.snippets).
NOTE: This is extended from the [haskell](./haskell.snippets) snippets.

## Lua Snippets

You can view the snippet [here](./lua.snippets).

* `#!`: #!/usr/bin/env lua
* `assert`: Assertion
* `!fun(ction)?!`: New function
* `forp`: pair for loop
* `fori`: ipair for foop
* `for`: numeric for loop
* `do`: do block
* `repeat`: repeat loop
* `while`: while loop
* `if`: if statement
* `ife`: if/else statement
* `eif`: if/elseif statement
* `eife`: if/elseif/else statement
* `pcall`: pcall statement
* `local`: local x = 1
* `use`: Use
* `req`: Require

## Mail Snippets

You can view the snippet [here](./mail.snippets).

* `temp`: Basic email template

## Mako Snippets

You can view the snippet [here](./mako.snippets).

* `def`: definition
* `call`: call
* `doc`: doc
* `text`: text
* `for`: for
* `if`: if 
* `if`: if/else
* `try`: try
* `wh`: wh
* `$`: $
* `<%`: <%
* `<!%`: \<!%
* `inherit`: inherit
* `include`: include
* `namespace`: namespace
* `page`: page

## Markdown Snippets

You can view the snippet [here](./markdown.snippets).

### Sections and Paragraphs

* `sec`: Section
* `ssec`: Sub Section
* `sssec`: SubSub Section
* `par`: Paragraph
* `spar`: Paragraph

### Text Formatting

* `*`: Italics
* `**`: Bold
* `***`: Bold italics
* `/*`: Comment

### Common Stuff

* `link`: Link to something
* `img`: Image
* `ilc`: Inline Code
* `cbl`: Codeblock
* `refl`: Reference Link
* `fnt`: Footnote
* `detail`: Disclosure
* `tb`: Create Table

## Matlab Snippets

You can view the snippet [here](./matlab.snippets).

* `switch`: switch ... otherwise
* `clc`: class with constructor

## Objc Snippets

You can view the snippet [here](./objc.snippets).

* `imp`: #import (imp)
* `Imp`: #import <> (Imp)
* `cl`: 020 Class (objc)
* `array`: NSArray (array)
* `dict`: NSDictionary (dict)
* `forarray`: for NSArray loop (forarray)
* `objacc`: Object Accessors (objacc)
* `sel`: @selector
* `cdacc`: CoreData Accessors Implementation
* `delegate`: Delegate Responds to Selector
* `thread`: Detach New NSThread
* `ibo`: IBOutlet (ibo)
* `I`: Initialize Implementation (I)
* `bind`: Key:value binding (bind)
* `arracc`: LoD array (arracc)
* `arracc`: LoD array interface (arracc)
* `focus`: Lock Focus
* `pool`: NSAutoreleasePool (pool)
* `log`: NSLog (log) 2
* `alert`: NSRunAlertPanel (alert)
* `format`: NSString stringWithFormat (format)
* `objacc`: Object Accessors Interface (objacc)
* `prop`: Property
* `getprefs`: Read from defaults (getprefs)
* `obs`: Register for Notification
* `responds`: Responds to Selector
* `gsave`: Save and Restore Graphics Context (gsave)
* `acc`: Scalar Accessors (acc)
* `acc`: Scalar Accessors Interface (acc)
* `stracc`: String Accessors (stracc)
* `syn`: Synthesize
* `setprefs`: Write to defaults (setprefs)

## Ocaml Snippets

You can view the snippet [here](./ocaml.snippets).

* `rs`: raise
* `open`: open
* `try`: try
* `ref`: ref
* `matchl`: pattern match on a list
* `matcho`: pattern match on an option type
* `fun`: anonymous function
* `cc`: commment
* `let`: let .. in binding
* `lr`: let rec
* `if`: if
* `If`: If
* `while`: while
* `for`: for
* `match`: match
* `Match`: match
* `class`: class
* `obj`: obj
* `Obj`: object
* `{{`: object functional update
* `beg`: beg
* `ml`: module instantiantion with functor
* `mod`: module - no signature
* `Mod`: module with signature
* `sig`: anonymous signature
* `sigf`: functor signature or anonymous functor
* `func`: define functor - no signature
* `Func`: define functor - with signature
* `mot`: Declare module signature
* `module`: Module with anonymous signature
* `oo`: odoc
* `qt`: inline qtest

## Octave Snippets

You can view the snippet [here](./octave.snippets).
NOTE: This is extended from the [matlab](./matlab.snippets) snippets.

## Pandoc Snippets

You can view the snippet [here](./pandoc.snippets).

* `title`: Title header

## Perl Snippets

You can view the snippet [here](./perl.snippets).

* `ife`: Conditional if..else (ife)
* `ifee`: Conditional if..elsif..else (ifee)
* `xunless`: Conditional one-line (unless)
* `xif`: Conditional one-line (xif)
* `sub`: Function (sub)
* `xfore`: Loop one-line (xforeach)
* `xwhile`: Loop one-line (xwhile)
* `test`: Test
* `class`: class
* `eval`: eval
* `for`: for
* `fore`: foreach
* `if`: if
* `slurp`: slurp
* `unless`: unless
* `while`: while
* `until`: until

## Php laravel Snippets

You can view the snippet [here](./php-laravel.snippets).

* `l_rsc`: Laravel resource controller
* `l_ssp`: Laravel service provider for service
* `l_rsp`: Laravel service provider for repository
* `l_md`: Laravel simple model
* `l_ar`: Laravel abstract Repository
* `l_r`: Laravel Repository
* `l_s`: Laravel Service
* `l_f`: Laravel Facade

## Php phpspec Snippets

You can view the snippet [here](./php-phpspec.snippets).

* `spec`: class XYZSpec extends ObjectBehaviour
* `it`: function it_does_something() { ... }
* `let`: function let() { ... }
* `letgo`: function letgo() { ... }
* `cw`: \$this->beConstructedWith($arg)
* `ct`: \$this->beConstructedThrough($methodName, [$arg])
* `sreturn`: \$this->XYZ()->shouldReturn('value')
* `snreturn`: \$this->XYZ()->shouldNotReturn('value')
* `sbe`: \$this->XYZ()->shouldBe('value')
* `snbe`: \$this->XYZ()->shouldNotBe('value')
* `sequal`: \$this->XYZ()->shouldEqual('value')
* `snequal`: \$this->XYZ()->shouldNotEqual('value')
* `sbequalto`: \$this->XYZ()->shouldBeEqualTo('value')
* `snbequalto`: \$this->XYZ()->shouldNotBeEqualTo('value')
* `sblike`: \$this->XYZ()->shouldBeLike('value')
* `snblike`: \$this->XYZ()->shouldNotBeLike('value')
* `sthrowm`: \$this->shouldThrow('\Exception')->duringXYZ($arg)
* `sthrowi`: \$this->shouldThrow('\Exception')->duringInstantiation()
* `stype`: \$this->shouldHaveType('Type')
* `sntype`: \$this->shouldNotHaveType('Type')
* `srinstance`: \$this->shouldReturnAnInstanceOf('Type')
* `snrinstance`: \$this->shouldNotReturnAnInstanceOf('Type')
* `sbinstance`: \$this->shouldBeAnInstanceOf('Type')
* `snbinstance`: \$this->shouldNotBeAnInstanceOf('Type')
* `simplement`: \$this->shouldImplement('Type')
* `snimplement`: \$this->shouldNotImplement('Type')
* `sbstate`: \$this->shouldBeXYZ()
* `snbstate`: \$this->shouldNotBeXYZ()
* `scount`: \$this->XYZ()->shouldHaveCount(7)
* `sncount`: \$this->XYZ()->shouldNotHaveCount(7)
* `sbscalar`: \$this->XYZ()->shouldBeString|Array|Bool()
* `snbscalar`: \$this->XYZ()->shouldNotBeString|Array|Bool()
* `scontain`: \$this->XYZ()->shouldContain('value')
* `sncontain`: \$this->XYZ()->shouldNotContain('value')
* `skey`: \$this->XYZ()->shouldHaveKey('key')
* `snkey`: \$this->XYZ()->shouldNotHaveKey('key')
* `skeyvalue`: \$this->XYZ()->shouldHaveKeyWithValue('key', 'value')
* `snkeyvalue`: \$this->XYZ()->shouldNotHaveKeyWithValue('key', 'value')
* `sstart`: \$this->XYZ()->shouldStartWith('string')
* `snstart`: \$this->XYZ()->shouldNotStartWith('string')
* `send`: \$this->XYZ()->shouldEndWith('string')
* `snend`: \$this->XYZ()->shouldNotEndWith('string')
* `smatch`: \$this->XYZ()->shouldMatch('/wizard/i')
* `snmatch`: \$this->XYZ()->shouldNotMatch('/wizard/i')

## Php symfony2 Snippets

You can view the snippet [here](./php-symfony2.snippets).

* `classn`: Basic class with namespace snippet
* `contr`: Symfony2 controller
* `sfa`: Symfony 2 Controller action
* `act`: Symfony2 action
* `actt`: Symfony2 action and template
* `comm`: Symfony2 command
* `subs`: Symfony2 subscriber
* `transf`: Symfony2 form data transformer
* `ent`: Symfony2 doctrine entity
* `form`: Symfony2 form type
* `ev`: Symfony2 event
* `redir`: Symfony2 redirect
* `usecontroller`: Symfony2 use Symfony\..\Controller
* `usereauest`: Symfony2 use Symfony\..\Request
* `useroute`: Symfony2 use Sensio\..\Route
* `useresponse`: Symfony2 use Symfony\..\Response
* `usefile`: Symfony2 use Symfony\..\File
* `useassert`: Symfony2 use Symfony\..\Constraints as Assert
* `usetemplate`: Symfony2 use Sensio\..\Template
* `usecache`: Symfony2 use Sensio\..\Cache
* `usemethod`: Symfony2 use Sensio\..\Method
* `usearray`: Symfony2 use Doctrine\..\ArrayCollection
* `useorm`: Symfony2 use Doctrine\..\Mapping as ORM
* `usesecure`: Symfony2 use JMS\..\Secure

## Php Snippets

You can view the snippet [here](./php.snippets).

* `gm`: PHP Class Getter
* `sm`: PHP Class Setter
* `gs`: PHP Class Getter Setter
* `pub`: Public function
* `pro`: Protected function
* `pri`: Private function
* `pubs`: Public static function
* `pros`: Protected static function
* `pris`: Private static function
* `fu`: Function snip
* `new`: New class instance
* `ns`: namespace declaration
* `class`: Class declaration template
* `interface`: Interface declaration template
* `trait`: Trait declaration template
* `construct`: \__construct()
* `testcase6`: class XYZTest extends TestCase { ... }

## Plaintex Snippets

You can view the snippet [here](./plaintex.snippets)

### Environments

* `beg`: begin{} / end{}
* `doc`: Document
* `cnt`: Center
* `desc`: Description
* `lemma`: Lemma
* `prop`: Proposition
* `thrm`: Theorem
* `post`: postulate
* `prf`: Proof
* `def`: Definition
* `nte`: Note
* `prob`: Problem
* `corl`: Corollary
* `exm`: Example
* `ntn`: Notation
* `rep`: Repetition
* `prop`: Property
* `int`: Intuition
* `obs`: Observation
* `conc`: Conclusion
* `enum`: Enumerate
* `item`: Itemize
* `case`: cases
* `ali`: Align\*
* `ali`: Align
* `eqt`: Equation
* `fig`: Figure environment
* `tkz`: Tikz pgfplot
* `tbl`: Table environment
* `gentbl`: Generate table of \*width\* by \*height\*
* `tr`: Add table row of dimension ...

### Inline and Display Math

* `ilm`: Inline Math
* `dm`: Display Math

### Snippets for fast typing

NOTE: These snippets only work when in **math mode**

* `<>`: If and only if
* `=>`: Implies
* `=<`: Implied by
* `if`: If and only if
* `|->`: Mapsto
* `+-`: Plus minus
* `-+`: Minus plus
* `*`: Times
* `-:-`: Divide
* `...`: Straight dots
* `.v`: Vertical dots
* `.a`: Dots above line
* `.d`: Diagonal dots
* `:.`: Therefore
* `<x|`: \bra{x}
* `|x>`: \ket{x}
* `\bra{x}x>` \braket{1}{c}

### Equality

NOTE: These snippets only work when in **math mode**

* `<<`: Less than
* `>>`: Greater than
* `<=`: Less than or equal to
* `>=`: Greater than or equal to
* `!=`: Not equal to
* `~=`: Approximately
* `===`: Equivalent
* `def=`: Defeq

### Other math symbols

NOTE: These snippets only work when in **math mode**

* `oo`: Infinity
* `oc`: Proportional

### Sub and Superscript

NOTE: These snippets only work when in **math mode**

* `a1`: Auto subscript 1 (a\_1)
* `a_11`: Auto subscript 2 (a_{11})
* `a_{11}1`: Auto subscript 3+ (a_{111})
* `sq`: Square
* `cb`: Cube
* `compl`: Complement
* `inv`: Inverse
* `ss`: Superscript
* `sr`: Square root
* `nr`: n Root

### Fractions

NOTE: These snippets only work when in **math mode**

* `//`: Fraction
* `4/`: Fraction (\frac{4}{})
* `(58 + 3)`: Fraction (\frac{58 + 3}{})

### Over text type

NOTE: These snippets only work when in **math mode**

* `bar`: Bar
* `abar`: Bar (\bar{a})
* `hat`: Hat
* `ahat`: Hat (\hat{a})
* `adot`: Dot (\dot{a})
* `f.,`: Vector Postfix (\vec{f})
* `f,.`: Vector Postfix (\vec{f})

### Sums and Products

NOTE: These snippets only work when in **math mode**

* `sum`: Sum
* `prod`: Product
* `taylor`: Taylor series

### Calculus

NOTE: These snippets only work when in **math mode**

* `int`: Indefinite integral
* `dint`: Definite integral
* `lim`: Limit
* `odx`: d/dx
* `ody`: d/dx
* `odt`: d/dx
* `od`: d/dx
* `pd`: d/dx
* `md`: d/dx
* `eval`: Eval int
* `nab`: Nabla
* `grad`: Nabla

### Real Analysis

NOTE: These snippets only work when in **math mode**

* `ext`: Exists
* `next`: Exists
* `lt`: Lnot
* `ld`: Land
* `for`: For all
* `qd`: Quad
* `mb`: Mathbb
* `inn`: In
* `RR`: Real numbers
* `ZZ`: Integer numbers
* `NN`: Natural numbers
* `QQ`: Rational numbers
* `PP`: Irrational numbers

### Matrices and Vectors

NOTE: These snippets only work when in **math mode**

* `mat`: Matrix
* `det`: Determinant matrix
* `vec`: Vector
* `matil`: Inline matrix
* `detil`: Inline determinant
* `vecil`: Inline vector
* `choose`: n choose p

### (), [], {}, and their bigger Counterparts #

NOTE: These snippets only work when in **math mode**

* `()`: Parenthesis
* `{}`: Parenthesis
* `[]`: Parenthesis
* `(`: Left(
* `)`: Right)
* `{`: Left{
* `}`: Right}
* `[`: Left[
* `]`: Right]

### TikZ

NOTE: These snippets only work when in **TikZPicture Environment**

* `circ`: Draw circle
* `elps`: Draw ellipse
* `arc`: Draw arc
* `line`: Draw line
* `multline`: Draw multiple lines
* `rect`: Draw rectangle
* `node`: Draw node
* `rgb`: Draw rgb color
* `mix`: Draw mixed color
* `colors`: All colors
* `thickness`: Line thickness
* `styles`: Line styles
* `tips`: Arrow tips
* `join`: Joining
* `bend`: Bend
* `coordinates`: Graph the Coordinates

### Qed Qea

* `qed`: Q.E.D.
* `qea`: Q.E.A.

### Lessons

* `les`: Lesson
* `lec`: Lecture

### Sections

* `chap`: Chapter
* `sec`: Subsection
* `sec*`: Subsection
* `sub`: Subsection
* `sub*`: Subsection
* `subsub`: Subsubsection
* `subsub*`: Subsubsection
* `par`: Paragraph
* `par*`: Paragraph
* `subpar`: Paragraph
* `subpar*`: Paragraph

### Text Edit

* `bf`: Bold
* `it`: Italic
* `un`: Underline
* `rm`: Text (Only works when in math mode)

### Preamble

* `pac`: Package

### Run code straight from the latex file, such as sympy, maybe eval or matplotlib #

* `sympy`: Sympy block 
* `sympy(.*)sympy`: Evaluate sympy
* `math`: Mathematica block
* `math(.*)math`: Evaluate mathematica

### Chemistry

* `react`: Reaction
* `*react`: Reaction no num
* `ce`: ce
* `CH2`: C with H on top and bottom
* `COOH`: Carboxyl
* `CH=O`: Aldehyde
* `CHO`: Carbonyl
* `CH-OH`: Hydroxide
* `CONH2`: Carboxyamide
* `COOC`: Ester

### Other

* `date`: Today's date and Current Time
* `sign`: Signature
* `ref`: Reference
* `link`: Hyperlink
* `itm`: New Item (Only works in the **itemize** or **enumerate** environment)
* `box`: Create box
* `ac`: Acroynm normal
* `acl`: Acroynm expanded
* `ni`: Non-indented paragraph
* `newp`: New Page

## Plsql Snippets

You can view the snippet [here](./plsql.snippets).

* `doc`: Document comment
* `hdr`: Header Documentation
* `pkggbl`: Package Global variables
* `flushca`: Flush Cache
* `flushsp`: Flush Shared Pool
* `sel`: Select statement
* `selc`: Select statement
* `wrn`: Where ROWNNUM
* `arn`: AND ROWNNUM
* `ppram`: Retuns param in wrapped format
* `dbo`: Show output 
* `dbop`: Show Parameter output 
* `dbl`: Log message in Log Table, Change procedure as defined by you
* `plog`: Print Log output 
* `dut`: DBMS_OUTPUT.put_line
* `bc`: Bulk collect into
* `ei`: Execute Immediate
* `eitt`: Execute Immediate TRUNCATE Table
* `eitp`: Execute Immediate ALTER Table Truncate partition
* `prmpt`: Prompt message
* `crseq`: Create Sequence
* `crsyn`: Create Synonym
* `crind`: Create Index
* `drtab`: Drop Table
* `crtab`: Create Table
* `ccol `: Add VARCHAR2 column to table
* `dcol `: Add DATE column to table
* `ncol `: Add NUMBER column to table
* `at`: Alter Table
* `tr`: Type record
* `tt`: Type Table
* `tc`: Type Cursor
* `if`: If Condition
* `ife`: IF-Else Condition
* `els`: Else Condition
* `case`: Case statement
* `while`: While Loop
* `fori`: For Loop
* `fort`: Table For Loop
* `loop`: Loop statement
* `fora`: For All Loop
* `forc`: For Cursor Loop
* `dcur`: Cursor declaration
* `copen`: Open Cursor
* `copenbc`: Open Cursor Bulk collect
* `decl`: Declare Begin block
* `begin`: Begin block
* `excp`: Exception Block
* `rae`: Raise Application Error
* `crjob`: Submit DBMS Job
* `whilejob`: Submit DBMS Job with While Loop
* `crgeterr`: Create get_errmsg function
* `crpksfunc`: Create package specification function
* `crpksproc`: Create package specification procedure
* `crpkbfunc`: Create package body function
* `crpkbproc`: Create package body procedure
* `crpks`: Create Package specification
* `crpkb`: Create package body
* `crproc`: Create procedure

## Proto Snippets

You can view the snippet [here](./proto.snippets).

* `mess`: Proto message
* `reqf`: Required field
* `optf`: Optional field
* `repf`: Repeated field
* `enum`: Enumeration

## Puppet Snippets

You can view the snippet [here](./puppet.snippets).

* `class`: Class declaration
* `define`: Definition
* `type`: Data type alias
* `lambda`: Lambda function chain-called on a variable
* `cron`: Cron resource type
* `exec`: Exec resource type
* `file`: File resource type
* `File`: Defaults for file
* `group`: Group resource type
* `mount`: Mount resource type
* `package`: Package resource type
* `user`: user resource type
* `service`: Service resource type
* `alert`: Alert Function
* `crit`: Crit Function
* `debug`: Debug Function
* `defined`: Defined Function
* `emerg`: Emerg Function
* `extlookup`: Simple Extlookup
* `extlookup`: Extlookup with defaults
* `extlookup`: Extlookup with defaults and custom data file
* `fail`: Fail Function
* `hiera`: Hiera Function
* `hiera`: Hiera with defaults
* `hiera`: Hiera with defaults and override
* `hiera_hash`: Hiera Hash Function
* `hiera_hash`: Hiera Hash with defaults
* `hiera_hash`: Hiera Hash with defaults and override
* `hiera_include`: Hiera Include Function
* `lookup`: Lookup data from hiera
* `trocla`: Lookup or generate sensitive information
* `include`: Include Function
* `info`: Info Function
* `inline_template`: Inline Template Function
* `notice`: Notice Function
* `realize`: Realize Function
* `regsubst`: Regsubst Function
* `split`: Split Function
* `versioncmp`: Version Compare Function
* `warning`: Warning Function

## Python Snippets

You can view the snippet [here](./python.snippets).

* `#!`: #!/usr/bin/env python
* `#!2`: #!/usr/bin/env python2
* `#!3`: #!/usr/bin/env python3
* `^# ?[uU][tT][fF]-?8`: # encoding: UTF-8
* `ifmain`: ifmain
* `with`: with
* `for`: for loop
* `class`: class with docstrings
* `numeric`: methods for emulating a numeric type
* `deff`: function or class method
* `def`: function with docstrings
* `/(^|(?<=\W))\./`: self.
* `from`: from module import name
* `roprop`: Read Only Property
* `rwprop`: Read write property
* `if`: If
* `ife`: If / Else
* `ifee`: If / Elif / Else
* `try`: Try / Except
* `trye`: Try / Except / Else
* `tryf`: Try / Except / Finally
* `tryef`: Try / Except / Else / Finally
* `ae`: Assert equal
* `at`: Assert True
* `af`: Assert False
* `aae`: Assert almost equal
* `ar`: Assert raises
* `an`: Assert is None
* `ann`: Assert is not None
* `testcase`: pyunit testcase
* `doc`: doc block (triple quotes)
* `pmdoc`: pocoo style module doc string

## Rails Snippets

You can view the snippet [here](./rails.snippets).

* `anaf`: accepts_nested_attributes_for
* `tcbi`: Create binary column
* `tcb`: Create boolean column
* `clac`: Create controller class
* `tcda`: Create date column
* `tcdt`: Create datetime column
* `tcd`: Create decimal column
* `tcf`: Create float column
* `clact`: Create functional test class
* `tci`: Create integer column
* `tcl`: Create lock_version column
* `resources`: Create resources controller class
* `tcs`: Create string column
* `tct`: Create text column
* `tcti`: Create time column
* `tcts`: Create timestamp column
* `tctss`: Create timestamps columns
* `mcol`: Migration Create Column (mcc)
* `mccc`: Migration Create Column Continue (mccc)
* `mtab`: Migration Drop Create Table (mdct)
* `mcol`: Migration Remove and Add Column (mrac)
* `rdb`: RAILS_DEFAULT_LOGGER.debug (rdb)
* `tre`: Table column(s) rename
* `art`: Test Assert Redirected To (art)
* `asre`: Test Assert Response (are)
* `aftc`: after_create
* `aftd`: after_destroy
* `afts`: after_save
* `aftu`: after_update
* `aftv`: after_validation
* `aftvoc`: after_validation_on_create
* `aftvou`: after_validation_on_update
* `asg`: assert(var = assigns(:var))
* `asd`: assert_difference
* `asnd`: assert_no_difference
* `artnpp`: assert_redirected_to (nested path plural)
* `artnp`: assert_redirected_to (nested path)
* `artpp`: assert_redirected_to (path plural)
* `artp`: assert_redirected_to (path)
* `asrj`: assert_rjs
* `ass`: assert_select
* `befc`: before_create
* `befd`: before_destroy
* `befs`: before_save
* `befu`: before_update
* `befv`: before_validation
* `befvoc`: before_validation_on_create
* `befvou`: before_validation_on_update
* `bt`: belongs_to (bt)
* `crw`: cattr_accessor
* `defcreate`: def create - resource
* `test`: test do..end
* `deftg`: def get request
* `deftp`: def post request
* `fina`: find(:all)
* `finf`: find(:first)
* `fini`: find(id)
* `fine`: find_each
* `finb`: find_in_batches
* `habtm`: has_and_belongs_to_many (habtm)
* `hm`: has_many (hm)
* `hmt`: has_many (through)
* `hmd`: has_many dependent: :destroy
* `ho`: has_one (ho)
* `logd`: logger.debug
* `loge`: logger.error
* `logf`: logger.fatal
* `logi`: logger.info
* `logw`: logger.warn
* `mp`: map(&:sym_proc)
* `mapca`: map.catch_all
* `map`: map.named_route
* `mapr`: map.resource
* `maprs`: map.resources
* `mapwo`: map.with_options
* `mrw`: mattr_accessor
* `ncl`: named_scope lambda
* `nc`: named_scope
* `dscope`: default_scope
* `flash`: flash[...]
* `rea`: redirect_to (action)
* `reai`: redirect_to (action, id)
* `rec`: redirect_to (controller)
* `reca`: redirect_to (controller, action)
* `recai`: redirect_to (controller, action, id)
* `renpp`: redirect_to (nested path plural)
* `renp`: redirect_to (nested path)
* `repp`: redirect_to (path plural)
* `rep`: redirect_to (path)
* `reb`: redirect_to :back
* `ra`: render (action)... (ra)
* `ral`: render (action,layout) (ral)
* `rf`: render (file) (rf)
* `rfu`: render (file,use_full_path) (rfu)
* `ri`: render (inline) (ri)
* `ril`: render (inline,locals) (ril)
* `rit`: render (inline,type) (rit)
* `rl`: render (layout) (rl)
* `rn`: render (nothing) (rn)
* `rns`: render (nothing,status) (rns)
* `rt`: render (text) (rt)
* `rtl`: render (text,layout) (rtl)
* `rtlt`: render (text,layout => true) (rtlt)
* `rts`: render (text,status) (rts)
* `ru`: render (update)
* `rest`: respond_to
* `cmm`: Create Migration Model Class
* `t.`: t.binary (tcbi)
* `t.`: t.boolean (tcb)
* `t.`: t.date (tcda)
* `t.`: t.datetime (tcdt)
* `t.`: t.decimal (tcd)
* `t.`: t.float (tcf)
* `t.`: t.integer (tci)
* `t.`: t.lock_version (tcl)
* `t.`: t.references (tcr)
* `t.`: t.rename (tre)
* `t.`: t.string (tcs)
* `t.`: t.text (tct)
* `t.`: t.time (tcti)
* `t.`: t.timestamp (tcts)
* `t.`: t.timestamps (tctss)
* `vaoif`: validates_acceptance_of if
* `vao`: validates_acceptance_of
* `va`: validates_associated (va)
* `vaif`: validates_associated if (vaif)
* `vc`: validates_confirmation_of (vc)
* `vcif`: validates_confirmation_of if (vcif)
* `ve`: validates_exclusion_of (ve)
* `veif`: validates_exclusion_of if (veif)
* `vfif`: validates_format_of if
* `vf`: validates_format_of
* `viif`: validates_inclusion_of if
* `vi`: validates_inclusion_of
* `vl`: validates_length_of (vl)
* `vlif`: validates_length_of if
* `vnif`: validates_numericality_of if
* `vn`: validates_numericality_of
* `vp`: validates_presence_of (vp)
* `vpif`: validates_presence_of if (vpif) 2
* `vu`: validates_uniqueness_of (vu)
* `vuif`: validates_uniqueness_of if (vuif)
* `verify`: verify -- render
* `verify`: verify -- redirect
* `wants`: wants_format
* `xdelete`: xhr delete
* `xget`: xhr get
* `xpost`: xhr post
* `xput`: xhr put
* `sweeper`: Create sweeper class
* `col`: collection routes
* `format`: format (respond_with)
* `gem`: gem
* `gemg`: gem :git
* `match`: match
* `member`: member routes
* `res`: resources
* `scope`: scope
* `scopel`: scope lambda
* `scopee`: scope with extension
* `sb`: scoped_by
* `setup`: setup do..end
* `trans`: Translation snippet

## Rnoweb Snippets

You can view the snippet [here](./rnoweb.snippets).

## Robot Snippets

You can view the snippet [here](./robot.snippets).

NOTE: This is extended from the [tex](./plaintex.snippets) snippets.
NOTE: This is extended from the [r](./r.snippets) snippets.

## R Snippets

You can view the snippet [here](./r.snippets).

* `ppet #!`: #!/usr/bin/env Rscript
* `ppet setwd`: Set workingdir
* `ppet as`: Apply type on variable
* `ppet is`: Test type on variable
* `ppet dl`: Download and install a package
* `ppet lib`: Import a library
* `ppet req`: Require a file
* `ppet source`: Source a file
* `ppet if`: If statement
* `ppet eif`: Else-If statement
* `ppet el`: Else statement
* `ppet ife`: if .. else
* `ppet wh`: while loop
* `ppet for`: for loop
* `ppet fun`: Function definition
* `ppet ret`: Return call
* `ppet df`: Data frame
* `ppet c`: c function
* `ppet li`: list function
* `ppet mat`: matrix function
* `ppet apply`: apply function
* `ppet lapply`: lapply function
* `ppet sapply`: sapply function
* `ppet vapply`: vapply function
* `ppet mapply`: mapply function
* `ppet tapply`: tapply function
* `ppet rapply`: rapply function
* `ppet pl`: Plot function
* `ppet ggp`: ggplot2 plot
* `ppet fis`: Fisher test
* `ppet chi`: Chi Squared test
* `ppet tt`: t-test
* `ppet wil`: Wilcox test
* `ppet cor`: Correlation test
* `ppet fte`: FTE test

## Rst Snippets

You can view the snippet [here](./rst.snippets).

* `part`: Part
* `chap`: Chapter
* `sec`: Section
* `ssec`: Subsection
* `sssec`: Subsubsection
* `para`: Paragraph
* `em`: Emphasize string
* `st`: Strong string
* `cb`: Code Block
* `id`: Includable Directives
* `di`: Directives
* `dt`: Directives without title
* `ds`: Directives for subscription
* `sa`: Specific Admonitions
* `ro`: Text Roles
* `eu`: Embedded URI
* `fnt`: Footnote or Citation
* `chart`: Pygal chart for Nikola
* `sid`: SideBar

## Rust Snippets

You can view the snippet [here](./rust.snippets).

* `fn`: fn name(?) -> ? {}
* `pfn`: pub fn name(?) -> ? {}
* `afn`: async fn name(?) -> ? {}
* `pafn`: pub async fn name(?) -> ? {}
* `pri`: print!(..)
* `pln`: println!(..)
* `fmt`: format!(..)
* `.it`: .iter()
* `impl`: Struct/Trait implementation

## Sh Snippets

You can view the snippet [here](./sh.snippets).

* `#!`: #!/usr/bin/env (!env)
* `sbash`: safe bash options
* `temp`: Tempfile
* `/case|sw(itch)?/`: case .. esac (case)
* `elif`: elif .. (elif)
* `for`: for ... done (for)
* `forin`: for ... in ... done (forin)
* `here`: here document (here)
* `/ift(est)?/`: if ... then (if)
* `if`: if ... then (if)
* `until`: until ... (done)
* `/wh(ile)?/`: while ... (done)
* `func`: function() {...}

## Snippets Snippets

You can view the snippet [here](./snippets.snippets).

* `usnip`: Ultisnips snippet definition
* `global`: Global snippet

## Soy Snippets

You can view the snippet [here](./soy.snippets).

NOTE: This is extended from the [html](./html.snippets) snippets.

## Supercollider Snippets

You can view the snippet [here](./supercollider.snippets).

* `for`: For loop
* `sdef`: SynthDef

## Svelte Snippets

You can view the snippet [here](./svelte.snippets).

NOTE: This is extended from the [html](./html.snippets) snippets.
NOTE: This is extended from the [javascript](./javascript.snippets) snippets.
NOTE: This is extended from the [css](./css.snippets) snippets.

## Tcl Snippets

You can view the snippet [here](./tcl.snippets).

* `for`: for... (for)
* `foreach`: foreach... (foreach)
* `if`: if... (if)
* `proc`: proc... (proc)
* `switch`: switch... (switch)
* `while`: while... (while)

## Typescript react Snippets

You can view the snippet [here](./typescript_react.snippets).

NOTE: This is extended from the [javascript react](./javascript-react.snippets) snippets.
NOTE: This is extended from the [typescript](./typescript.snippets) snippets.

## Typescript Snippets

You can view the snippet [here](./typescript.snippets).

NOTE: This is extended from the [javascript](./javascript.snippets) snippets.

## Vim Snippets

You can view the snippet [here](./vim.snippets).

* `gvar`: Global / configuration variable
* `guard`: Script reload guard
* `f`: Function

## Vue Snippets

You can view the snippet [here](./vue.snippets).

NOTE: This is extended from the [javascript](./javascript.snippets) snippets.
NOTE: This is extended from the [html](./html.snippets) snippets.
NOTE: This is extended from the [css](./css.snippets) snippets.

## Xhtml Snippets

You can view the snippet [here](./xhtml.snippets).

NOTE: This is extended from the [html](./html.snippets) snippets.

## Xml Snippets

You can view the snippet [here](./xml.snippets).

* `xml`: XML Declaration
* `t`: Simple tag
* `ti`: Inline tag

## Zsh Snippets

You can view the snippet [here](./zsh.snippets).

NOTE: This is extended from the [sh](./sh.snippets) snippets.

* `#!`: #!/usr/bin/env zsh
