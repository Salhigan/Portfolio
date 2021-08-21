<template>
    <div id="music">
        <section class="container">
            <h2 id="Musique">Musique</h2>
            <div id="s-card">
                <iframe width="25%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/297118756&color=%234484e4&auto_play=false&hide_related=false&show_comments=false&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
                <iframe width="25%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/333671729&color=%233ddfb3&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
                <iframe width="25%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/467213991&color=%236b584e&auto_play=false&hide_related=false&show_comments=false&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
            </div>
            <div id="s-text">
                <div style="font-size: 18px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/salhigan" title="Salhigan" target="_blank" style="color: #fff; text-decoration: none;">Salhigan</a> · <a href="https://soundcloud.com/salhigan/sets/chip-a-tune" title="Chip &#x27;A&#x27; Tune" target="_blank" style="color: #5dd9d3; text-decoration: none;">Chip &#x27;A&#x27; Tune</a></div>
                <div style="font-size: 18px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/salhigan" title="Salhigan" target="_blank" style="color: #fff; text-decoration: none;">Salhigan</a> · <a href="https://soundcloud.com/salhigan/sets/chiptune-b" title="Chiptune B" target="_blank" style="color: #fb3573; text-decoration: none;">Chiptune B</a></div>
                <div style="font-size: 18px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/salhigan" title="Salhigan" target="_blank" style="color: #fff; text-decoration: none;">Salhigan</a> · <a href="https://soundcloud.com/salhigan/sets/swing-of-owls" title="Swing of Owls" target="_blank" style="color: #ecdace; text-decoration: none;">Swing of Owls</a></div>
            </div>
        </section>
    </div>
</template>

<script>

export default ({
    name:'Musique'
})
</script>

<style scoped>
#s-card {
    display: flex;
    justify-content: space-around;
    align-items: center;

    padding: 0 20px;
}
#s-text {
    display: flex;
    justify-content: space-around;
    align-items: center;

    padding: 20px;
}
</style>
