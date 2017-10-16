# Hello-World
/*This is a web application using mySQL and VisualStudio.
The chosen framework to accomplish this project was using ASP.NET. 
*/
@{
    ViewBag.Title = "Home Page";
}

<div class="jumbotron">
    <h1>ASP.NET</h1>
    <p class="lead">ASP.NET is a free web framework for building great Web sites and Web applications using HTML, CSS and JavaScript.</p>
    <p><a href="https://asp.net" class="btn btn-primary btn-lg">Learn more &raquo;</a></p>
</div>

<div class="row">
    <div class="col-md-4">
        <h2>Getting started</h2>
        <p>
            @Html.ActionLink("Patients ","Index","Patients") |
            @Html.ActionLink("Medical Records ", "Index", "MedicalRecords") |
            @Html.ActionLink("Record Entries ", "Index", "RecordEntries") |
            @Html.ActionLink("Record Type ", "Index", "RecordTypes") |
            @Html.ActionLink("Treatments ", "Index", "Treatments") |
            @Html.ActionLink("Applied Treatments ", "Index", "AppliedTreatments") |
        </p>
       <p><a class="btn btn-default" href="https://go.microsoft.com/fwlink/?LinkId=301865">Learn more &raquo;</a></p>
    </div>
    <div class="col-md-4">
        <h2>Get more libraries</h2>
        <p>NuGet is a free Visual Studio extension that makes it easy to add, remove, and update libraries and tools in Visual Studio projects.</p>
        <p><a class="btn btn-default" href="https://go.microsoft.com/fwlink/?LinkId=301866">Learn more &raquo;</a></p>
    </div>
    <div class="col-md-4">
        <h2>Web Hosting</h2>
        <p>You can easily find a web hosting company that offers the right mix of features and price for your applications.</p>
        <p><a class="btn btn-default" href="https://go.microsoft.com/fwlink/?LinkId=301867">Learn more &raquo;</a></p>
    </div> 
    
</div>
