# tembryo-website

docker commands:

	sudo docker build -t tembryo-webserver .

run:

    sudo docker run --name tembryo-web -d -e VIRTUAL_HOST="tembryo.com,www.tembryo.com" -v /usr/local/tembryo-website/src:/var/www --expose=80 tembryo-webserver

## template code

    <a href="#about" class="btn btn-dark btn-lg">Find Out More</a>

<div class="col-md-3 col-sm-6">
    <div class="service-item">
        <span class="fa-stack fa-4x">
        <i class="fa fa-circle fa-stack-2x"></i>
        <i class="fa fa-cloud fa-stack-1x text-primary"></i>
    </span>
        <h4>
            <strong>Service Name</strong>
        </h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        <a href="#" class="btn btn-light">Learn More</a>
    </div>
</div>
