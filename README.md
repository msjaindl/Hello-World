# Hello-World

/*This is a web application using mySQL and VisualStudio.
The chosen framework to accomplish this proect was ASP.NET
*/
@{
    ViewBag.Title = "Home Page";
}

<div class="jumbotron">
    <h1>Tumor Taskforce</h1>
    <p class="lead">This ASP.NET application was created using mySQL and Visual Studio.</p>
    
</div>

<div class="row">
    <div class="col-md-4">
        <h2>Getting Started</h2>
        <p>
          @Html.ActionLink("Patients ","Index","Patients") | @Html.ActionLink("Medical Records ", "Index", "MedicalRecords") |
          @Html.ActionLink("Record Entries ", "Index", "RecordEntries") | @Html.ActionLink("Record Type ", "Index", "RecordTypes") |
          @Html.ActionLink("Treatments ", "Index", "Treatments") | @Html.ActionLink("Applied Treatments ", "Index", "AppliedTreatments") |
        </p>
       
    
</div>
=======
This is the initial stages of a web application using mySQL and VisualStudio 

