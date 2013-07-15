Bootstrap Phila.gov Theme
=========================
Phila.gov style bootstrap theme. This repo exists to keep phila.gov bootstrap sites themes in sync. Example usage at [avicalculator.phila.gov](http://avicalculator.phila.gov) and [phila.gov/map](http://www.phila.gov/map).

To install in your repo, [use it as a submodule](http://stackoverflow.com/questions/4161022/git-how-to-track-untracked-content):

`git submodule add git://github.com/CityOfPhiladelphia/bootstrap-philagov.git path/to/desired/folder`

(note the public/non-ssh url of the repo, [required for heroku](http://stackoverflow.com/questions/13362288/heroku-push-rejected-submodule-install-failed))

To include the phila.gov navbar,

    <div class="navbar navbar-static-top">
        <div class="navbar-inner philagov">
            <div class="container">
				<a class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse">
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</a>
				<a class="brand" href="#"><img src="images/cityLogo-31px.png" alt="City Seal"></a>
				<span class="hidden-phone"><a class="brand" href="#"><img src="images/cityLogoMark-145-30.png" alt="City Logo"></a></span>
				<div class="nav-collapse collapse">
					<ul class="nav">
						<li><a title="City Homepage" href="http://www.phila.gov"><i class="icon-home icon-white"></i></a></li>
						<li><a title="Topics" href="http://www.phila.gov/Topics">Topics</a></li>
						<li><a title="Business" href="http://www.phila.gov/Business">Business</a></li>
						<li><a title="Residents" href="http://www.phila.gov/residents">Residents</a></li>
                        <li><a title="Visitors" href="http://www.phila.gov/visitors">Visitors</a></li>
                        <li><a title="Government" href="http://www.phila.gov/agencies">Government</a></li>
					</ul>
				</div>
			</div>
		</div>
        
        <!-- Optional Tools -->
        <div class="navbar-inner navbar-tools hidden-phone">
            <div class="container">
                <ul class="nav pull-left no-collapse">
                    <li class="active"><a href="#"><i class="icon-list"></i> <span class="hidden-phone">Browse</span></a></li>
                    <li><a href="#"><i class="icon-signal"></i> <span class="hidden-phone">Visualize</span></a></li>
                    <li><a href="#"><i class="icon-download-alt"></i> <span class="hidden-phone">Download</span></a></li>
                </ul>
            </div>
        </div>
        <!-- End Optional Tools -->
    </div>