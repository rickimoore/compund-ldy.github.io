<template>
    <main class="profile">
        <section>
            <div class="profile-info">
                <div class="profile-image"></div>
                <div class="profile-meta">
                    <div class="profile-peta">
                        <span class="profile-name">Marta Alejandra Gonzalez</span>
                        <button>Edit profile</button>
                    </div>
                    <div class="profile-subtitle">
                        Lives in Santa, Monica CA
                    </div>
                    <div class="profile-list">
                        <ul>
                            <li>Prefers permanent roles</li>
                            <li>Interested in contract roles</li>
                            <li>Open to part time roles</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="profile-links">
                <span>Resumé</span>
                <span>Personal Website</span>
                <span>Github</span>
                <span>LinkedIn</span>
                <span>Email</span>
            </div>
        </section>
        <section class="profile-box">
            <h4>Info</h4>
            <div>
                <i class="fa fa-cog fa-lg"></i>
                <span>Interested in Digital Marketing, User Research, Visual/UI Design roles</span>
            </div>
            <div class="location">
                <i class="fa fa-map-pin fa-lg"></i>
                <span>Willing to work in or near the following areas:</span>
            </div>
            <div class="cities">
                <span>1. Barcelona, Spain</span>
                <span>2. Madrid, Spain</span>
            </div>
        </section>
        <section class="profile-box tickets">
            <h4>Events</h4>
            <div>
                <i class="fa fa-calendar fa-lg"></i>
                <span class="eventText">Sustainability Jam, March 15</span>
                <span class="ticket">Download ticket</span>
            </div>
            <div class="location">
                <i class="fa fa-calendar fa-lg"></i>
                <span class="eventText">Meet you mentor, February 21</span>
                <span class="ticket">Download ticket</span>
            </div>
        </section>
    </main>
</template>
<script>
    export default{
        mounted(){
            console.log('this is the profile page');
        }
    }
</script>
