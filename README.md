
Sign up
quran
/
quran_android
Public
Code
Issues
229
Pull requests
10
Actions
Projects
Security
Insights
quran_android/quran_android-code_style.xml
@ahmedre
ahmedre Update code styles for Quran
…
 2 contributors
354 lines (354 sloc)  16.1 KB
<code_scheme name="quran_android-code_style">
  <option name="CLASS_COUNT_TO_USE_IMPORT_ON_DEMAND" value="99" />
  <option name="NAMES_COUNT_TO_USE_IMPORT_ON_DEMAND" value="99" />
  <option name="IMPORT_LAYOUT_TABLE">
    <value>
      <package name="com.google" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="android" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="antenna" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="antlr" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ar" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="asposewobfuscated" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="asquare" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="atg" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="au" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="beaver" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="bibtex" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="bmsi" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="bsh" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ccl" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="cern" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ChartDirector" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="checkers" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="com" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="COM" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="common" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="contribs" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="corejava" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="cryptix" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="cybervillains" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="dalvik" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="danbikel" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="de" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="EDU" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="eg" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="eu" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="examples" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="fat" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="fit" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="fitlibrary" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="fmpp" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="freemarker" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="gnu" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="groovy" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="groovyjarjarantlr" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="groovyjarjarasm" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="hak" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="hep" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ie" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="imageinfo" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="info" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="it" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jal" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="Jama" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="japa" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="japacheckers" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jas" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jasmin" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="javancss" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="javanet" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="javassist" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="javazoom" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="java_cup" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jcifs" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jetty" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="JFlex" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jj2000" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jline" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jp" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="JSci" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jsr166y" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="junit" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jxl" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="jxxload_help" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="kawa" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="kea" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="libcore" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="libsvm" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="lti" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="memetic" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="mt" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="mx4j" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="net" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="netscape" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="nl" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="nu" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="oauth" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ognl" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="opennlp" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="oracle" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="org" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="penn2dg" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="pennconverter" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="pl" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="prefuse" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="proguard" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="repackage" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="scm" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="se" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="serp" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="simple" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="soot" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="sqlj" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="src" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ssa" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="sun" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="sunlabs" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="tcl" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="testdata" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="testshell" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="testsuite" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="twitter4j" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="uk" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="ViolinStrings" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="weka" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="wet" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="winstone" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="woolfel" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="wowza" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="java" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="javax" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="" withSubpackages="true" static="false" />
      <emptyLine />
      <package name="" withSubpackages="true" static="true" />
    </value>
  </option>
  <option name="RIGHT_MARGIN" value="100" />
  <option name="JD_P_AT_EMPTY_LINES" value="false" />
  <option name="JD_KEEP_EMPTY_PARAMETER" value="false" />
  <option name="JD_KEEP_EMPTY_EXCEPTION" value="false" />
  <option name="JD_KEEP_EMPTY_RETURN" value="false" />
  <option name="KEEP_CONTROL_STATEMENT_IN_ONE_LINE" value="false" />
  <option name="KEEP_BLANK_LINES_IN_CODE" value="1" />
  <option name="BLANK_LINES_AFTER_CLASS_HEADER" value="1" />
  <option name="ALIGN_MULTILINE_PARAMETERS_IN_CALLS" value="true" />
  <option name="ALIGN_MULTILINE_BINARY_OPERATION" value="true" />
  <option name="ALIGN_MULTILINE_ASSIGNMENT" value="true" />
  <option name="ALIGN_MULTILINE_TERNARY_OPERATION" value="true" />
  <option name="ALIGN_MULTILINE_THROWS_LIST" value="true" />
  <option name="ALIGN_MULTILINE_EXTENDS_LIST" value="true" />
  <option name="ALIGN_MULTILINE_PARENTHESIZED_EXPRESSION" value="true" />
  <option name="ALIGN_MULTILINE_ARRAY_INITIALIZER_EXPRESSION" value="true" />
  <option name="CALL_PARAMETERS_WRAP" value="1" />
  <option name="METHOD_PARAMETERS_WRAP" value="1" />
  <option name="EXTENDS_LIST_WRAP" value="1" />
  <option name="THROWS_LIST_WRAP" value="1" />
  <option name="EXTENDS_KEYWORD_WRAP" value="1" />
  <option name="THROWS_KEYWORD_WRAP" value="1" />
  <option name="METHOD_CALL_CHAIN_WRAP" value="1" />
  <option name="BINARY_OPERATION_WRAP" value="1" />
  <option name="BINARY_OPERATION_SIGN_ON_NEXT_LINE" value="true" />
  <option name="TERNARY_OPERATION_WRAP" value="1" />
  <option name="TERNARY_OPERATION_SIGNS_ON_NEXT_LINE" value="true" />
  <option name="FOR_STATEMENT_WRAP" value="1" />
  <option name="ARRAY_INITIALIZER_WRAP" value="1" />
  <option name="ASSIGNMENT_WRAP" value="5" />
  <option name="WRAP_COMMENTS" value="true" />
  <option name="IF_BRACE_FORCE" value="3" />
  <option name="DOWHILE_BRACE_FORCE" value="3" />
  <option name="WHILE_BRACE_FORCE" value="3" />
  <option name="FOR_BRACE_FORCE" value="3" />
  <AndroidXmlCodeStyleSettings>
    <option name="USE_CUSTOM_SETTINGS" value="true" />
    <option name="LAYOUT_SETTINGS">
      <value>
        <option name="INSERT_BLANK_LINE_BEFORE_TAG" value="false" />
        <option name="INSERT_LINE_BREAK_AFTER_LAST_ATTRIBUTE" value="true" />
      </value>
    </option>
  </AndroidXmlCodeStyleSettings>
  <Objective-C-extensions>
    <option name="GENERATE_INSTANCE_VARIABLES_FOR_PROPERTIES" value="ASK" />
    <option name="RELEASE_STYLE" value="IVAR" />
    <option name="TYPE_QUALIFIERS_PLACEMENT" value="BEFORE" />
    <file>
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Import" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Macro" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Typedef" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Enum" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Constant" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Global" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Struct" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="FunctionPredecl" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Function" />
    </file>
    <class>
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Property" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Synthesize" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="InitMethod" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="StaticMethod" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="InstanceMethod" />
      <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="DeallocMethod" />
    </class>
    <extensions>
      <pair source="cpp" header="h" />
      <pair source="c" header="h" />
    </extensions>
  </Objective-C-extensions>
  <XML>
    <option name="XML_LEGACY_SETTINGS_IMPORTED" value="true" />
  </XML>
  <ADDITIONAL_INDENT_OPTIONS fileType="haml">
    <option name="INDENT_SIZE" value="2" />
  </ADDITIONAL_INDENT_OPTIONS>
  <ADDITIONAL_INDENT_OPTIONS fileType="java">
    <option name="INDENT_SIZE" value="2" />
    <option name="CONTINUATION_INDENT_SIZE" value="4" />
    <option name="TAB_SIZE" value="8" />
  </ADDITIONAL_INDENT_OPTIONS>
  <ADDITIONAL_INDENT_OPTIONS fileType="js">
    <option name="CONTINUATION_INDENT_SIZE" value="4" />
  </ADDITIONAL_INDENT_OPTIONS>
  <ADDITIONAL_INDENT_OPTIONS fileType="sass">
    <option name="INDENT_SIZE" value="2" />
  </ADDITIONAL_INDENT_OPTIONS>
  <ADDITIONAL_INDENT_OPTIONS fileType="yml">
    <option name="INDENT_SIZE" value="2" />
  </ADDITIONAL_INDENT_OPTIONS>
  <codeStyleSettings language="JAVA">
    <option name="SPACE_WITHIN_ARRAY_INITIALIZER_BRACES" value="true" />
    <option name="CALL_PARAMETERS_WRAP" value="1" />
    <option name="METHOD_PARAMETERS_WRAP" value="1" />
    <option name="METHOD_CALL_CHAIN_WRAP" value="1" />
    <option name="FIELD_ANNOTATION_WRAP" value="1" />
    <option name="PARAMETER_ANNOTATION_WRAP" value="1" />
    <option name="VARIABLE_ANNOTATION_WRAP" value="1" />
    <indentOptions>
      <option name="INDENT_SIZE" value="2" />
      <option name="CONTINUATION_INDENT_SIZE" value="4" />
      <option name="TAB_SIZE" value="2" />
    </indentOptions>
  </codeStyleSettings>
  <codeStyleSettings language="XML">
    <indentOptions>
      <option name="INDENT_SIZE" value="2" />
      <option name="CONTINUATION_INDENT_SIZE" value="4" />
      <option name="TAB_SIZE" value="2" />
    </indentOptions>
  </codeStyleSettings>
</code_scheme>
