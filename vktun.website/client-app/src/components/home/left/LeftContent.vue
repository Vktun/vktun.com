<template>
    <div class="mt-4">
        <h5 class="text-left">Good Contents</h5>
        <b-card img-src="https://placekitten.com/300/180" img-alt="Card image" img-left class="mb-2">
            <b-card-text>Some quick example text to build on the card and make up the bulk of the card's content.</b-card-text>
        </b-card>
        <b-card img-src="https://placekitten.com/300/180" img-alt="Card image" img-right>
            <b-card-text>Some quick example text to build on the card and make up the bulk of the card's content.</b-card-text>
        </b-card>
        <b-card img-src="https://placekitten.com/300/180" img-alt="Card image" img-left class="mb-2 mt-2">
            <b-card-text>Some quick example text to build on the card and make up the bulk of the card's content.</b-card-text>
        </b-card>
        <b-card-group columns>
            <b-card title="Card title that wraps to a new line"
                    img-src="https://placekitten.com/g/400/450"
                    img-alt="Image"
                    img-top>
                <b-card-text>
                    This is a wider card with supporting text below as a natural lead-in to additional content.
                    This content is a little bit longer.
                </b-card-text>
            </b-card>

            <b-card header="Quote">
                <blockquote class="blockquote mb-0">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
                    <footer class="blockquote-footer">
                        Someone famous in <cite title="Source Title">Source Title</cite>
                    </footer>
                </blockquote>
            </b-card>

            <b-card title="Title"
                    img-src="https://placekitten.com/500/350"
                    img-alt="Image"
                    img-top>
                <b-card-text>
                    This card has supporting text below as a natural lead-in to additional content.
                </b-card-text>
                <b-card-text class="small text-muted">Last updated 3 mins ago</b-card-text>
            </b-card>

            <b-card bg-variant="primary" text-variant="white">
                <blockquote class="card-blockquote">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
                    <footer>
                        <small>Someone famous in <cite title="Source Title">Source Title</cite></small>
                    </footer>
                </blockquote>
            </b-card>

            <b-card>
                <b-card-title>Title</b-card-title>
                <b-card-text>
                    This card has supporting text below as a natural lead-in to additional content.
                </b-card-text>
                <b-card-text class="small text-muted">Last updated 3 mins ago</b-card-text>
            </b-card>

            <b-card img-src="https://picsum.photos/400/400/?image=41" img-alt="Image" overlay />

            <b-card img-src="https://picsum.photos/400/200/?image=41" img-alt="Image" img-top>
                <b-card-text>
                    This is a wider card with supporting text below as a natural lead-in to additional content.
                    This card has even longer content than the first.
                </b-card-text>
                <div slot="footer"><small class="text-muted">Footer Text</small></div>
            </b-card>
        </b-card-group>
    </div>
</template>

<script>
export default {};
</script>

<style>
</style>
