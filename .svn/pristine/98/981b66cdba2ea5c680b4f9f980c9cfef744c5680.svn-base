Imports System.IO

Public Class Form1

    Private Sub Button1_Click(sender As System.Object, e As System.EventArgs) Handles Button1.Click




        Dim FILE_NAME As String = "f:\20120302.cp"
        Dim TextLine As String = ""
        If System.IO.File.Exists(FILE_NAME) = True Then
            Dim objReader As New System.IO.StreamReader(FILE_NAME)
            Do While objReader.Peek() <> -1
                TextLine = TextLine & objReader.ReadLine() & vbNewLine
                Application.DoEvents()
            Loop
            TextBox1.Text = TextLine
        Else
            MsgBox("File Does Not Exist")
        End If
    End Sub
End Class
