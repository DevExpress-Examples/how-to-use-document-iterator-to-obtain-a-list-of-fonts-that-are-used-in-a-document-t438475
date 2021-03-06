<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
<!-- default file list end -->
# How to use Document Iterator to obtain a list of fonts that are used in a document


<p>This example creates a <a href="http://help.devexpress.com/#CoreLibraries/clsDevExpressXtraRichEditAPINativeDocumentIteratortopic">DocumentIterator</a> instance for the current document and calls its <a href="http://help.devexpress.com/#CoreLibraries/DevExpressXtraRichEditAPINativeDocumentIterator_MoveNexttopic">MoveNext</a> method to iterate through document elements. The <strong>Visitor pattern </strong>is implemented to process a document element. </p>
<p><strong>MyVisitor </strong>is a custom class inherited from the <a href="https://documentation.devexpress.com/CoreLibraries/DevExpress.XtraRichEdit.API.Native.DocumentVisitorBase.class">DocumentVisitorBase</a> class. This class provides a method that processes <a href="http://help.devexpress.com/#CoreLibraries/clsDevExpressXtraRichEditAPINativeDocumentTexttopic">DocumentText</a> elements, obtains a name of the font applied to the text element, and writes the font name in a list. <br><br>See also: <a href="https://www.devexpress.com/Support/Center/Example/Details/T384347">How to use the Document Iterator object to iterate over document elements</a>.</p>
