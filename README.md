<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Cool CS Bot</title>
    <link rel="icon" href="images/Bot_Logo.png" type="image/png">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles/style.css">
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar">
    <a class="nav-link active" data-target="home">Home</a>
    <a class="nav-link" data-target="quickstart">Quick Start Guide</a>
    <a class="nav-link" data-target="documentation">Documentation</a>
    <a class="nav-link" data-target="tos">Terms of Service</a>
    <a class="nav-link" data-target="privacy">Privacy Policy</a>
    <!-- <a class="nav-link" data-target="premium">Pricing</a> -->
</nav>

<!-- Lightbox overlay -->
<div id="lightbox" class="lightbox">
    <img id="lightbox-img" src="">
</div>

<!-- PAGE CONTENT WRAPPER (animated) -->
<main id="content" class="page-transition visible">

    <!-- ====================== HOME ====================== -->
    <section id="home" class="section active">
        <h1>Cool CS Bot</h1>

        <img class="bot-logo" src="images/Bot_Logo.png" alt="Bot Logo">

        <div class="center">
            <a class="invite-button" href="YOUR_INVITE_LINK" target="_blank">Invite Bot</a>
        </div>

        <div class="bot-description">
            <h2>A Better Discord Experience</h2>
            <div class="accent-text">
                

                <p>
                    <strong>This bot is built to enhance both user experience and server management</strong>.<br><br>
                    Why create dozens of voice channels when users can make their own (with full privacy controls)
                    and the bot cleans everything up automatically? And for CS2 players, nothing beats showing off
                    your Faceit elo or stats, both of which the bot handles with ease!<br><br>

                    Plus, you'll never miss a CS2 update again! The bot fetches new patches within minutes and
                    presents the notes in a clean, easy to read format.
                </p>
            </div>
            
            
            <div class="feature-list-wrapper fade-in-on-scroll">
                <div class="feature-list">
                    <ul>
                        <li>
                            <strong>Automated Faceit Elo Tracking</strong>
                            <p class="feature-desc">
                                Users can enter their Faceit username and have their elo updated every 24 hours.
                            </p>
                        </li>

                        <li>
                            <strong>Detailed Faceit Match History</strong>
                            <p class="feature-desc">
                                View stats for the last 10 games of any player, including Wins, Losses, average ADR and more!
                            </p>
                        </li>

                        <li>
                            <strong>Weekly Faceit Leaderboard</strong>
                            <p class="feature-desc">
                                Users can enter themselves into an automatically updated leaderboard where they can flex their
                                current elo, elo gains, elo losses or matches played in the last 7 days!
                            </p>
                        </li>

                        <li>
                            <strong>Voice Channel Management</strong>
                            <p class="feature-desc">
                                Users can create their own temporary voice channels with privacy controls:
                                make channels private, require join requests, or hide them entirely.<br><br>
                                Server owners can create permanent voice channels. These channels remain active
                                until an Admin deletes them and cannot be made private or hidden by users.
                            </p>
                        </li>

                        <li>
                            <strong>Update Notifications</strong>
                            <p class="feature-desc">
                                CS2 updates are fetched within minutes and posted on your server if this feature is
                                activated!
                            </p>
                        </li>

                        <li>
                            <strong>Looking-For-Players Feature</strong>
                            <p class="feature-desc">
                                No more spamming "someone from REGION wanting to play CS2 together?" in text channels. Users looking
                                for other CS2 players can create a LFP profile allowing others to add them!
                            </p>
                        </li>

                        <li>
                            <strong>...and many more!</strong>
                            <p class="feature-desc">
                                Additional utilities, QoL tools, and CS inspired features designed to
                                enhance your Discord server.
                            </p>
                        </li>
                    </ul>
                </div>
            </div>
        
        <div class="showcase">
            <h2>Enhanced Voice Channel Functionality and Privacy</h2>
            <div class="video-section">  
                <video class="interactive-video" muted playsinline>
                    <source src="videos/Dynamic Channels.mp4" type="video/mp4">
                </video>

                <video class="interactive-video" muted playsinline>
                    <source src="videos/Channel Privacy.mp4" type="video/mp4">
                </video>
            </div>
        </div>
        
        <div class="showcase">
            <h2>Faceit Stats, LFP and the Queue</h2>
            <div class="carousel">
                <button class="carousel-btn left">&lt;</button>

                <div class="carousel-window">
                    <img class="carousel-img active" src="images/Faceit Stats.png">
                    <img class="carousel-img" src="images/Leaderboard.png">
                    <img class="carousel-img" src="images/Queue.png">
                </div>

                <button class="carousel-btn right">&gt;</button>
            </div>
        </div>
    </div>

    </section>

    <!-- ====================== DOCUMENTATION ====================== -->
    <section id="documentation" class="section">
        <h1>Documentation</h1>
        
        <h2 class="doc-category-title">Owner Commands</h2>
        <table class="table-doc">
            <tr><th>Command</th><th>Parameters</th><th>Description</th></tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/server_setup</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Let the Bot setup the basics on your server.<br>Creates a Bot Category, Region Roles, a Queue Channel and a Bot Commands channel.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/server_reset</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Let the Bot reset your server.<br>Everything you or a user created in terms of channels will be deleted and everything in the
                    database regarding your server will also be wiped.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/server_leave</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Prompts the Bot to reset your server.<br>Everything you or a user created in terms of channels will be deleted and everything in the
                    database regarding your server will also be wiped.<br>The Bot will also leave the server afterwards.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/server_premium</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Activates premium status for your server, if you have a running subscription on Patreon.<br>
                    Note: It can take up to 24 hours until the activation is completed. And yes, it will be valid for 31 days
                    from the moment the activation is completed.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/patchnotes_subscribe</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Subscribes the channel the command was run in to receive notifications from the Bot whenever
                        a CS2 update drops.
                    </td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/patchnotes_unsubscribe</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Removes your server from receiving CS2 patchnotes.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/leaderboard_create</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Creates a leaderboard users can enter. This leaderboard displays various Faceit stats.<br>
                    If you want to remove the leaderboard, simply delete the created text-channel.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/bot_updates_subscribe</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Subscribes the channel the command was used in to receive development updates of the Bot.<br>
                    This includes mostly planned downtimes or incoming bugfixes.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/bot_updates_unsubscribe</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Removes any set channel for Bot updates from receiving notifications.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/ban</td>
                    <td>discord_name</td>
                </div>
                <div class="table-wrap">
                    <td>Bans the user from using any feature of the Bot on your server for 1 year and deletes all associated data
                        (e.g. Leaderboard entry, LFP profile, etc.).<br>
                        Note: discord_name is the unique profile name of the user (formerly name#1234), not their changable nickname on your server.
                    </td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/unban</td>
                    <td>discord_name</td>
                </div>
                <div class="table-wrap">
                    <td>Lifts the server wide ban from a user and allows them to use the bot again.
                    </td>
                </div>
            </tr>
        </table>

        <h2 class="doc-category-title">Faceit Commands</h2>
        <table class="table-doc">
            <tr><th>Command</th><th>Parameters</th><th>Description</th></tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/track_player</td>
                    <td>faceit_name</td>
                </div>
                <div class="table-wrap">
                    <td>Tracks the elo of the entered Faceit Nickname.<br>
                        The elo will be refreshed every 24 hours.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/untrack_player</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Stops tracking the elo of the Faceit Nickname you entered before.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/faceit_stats</td>
                    <td>faceit_name</td>
                </div>
                <div class="table-wrap">
                    <td>Displays various stats (e.g. average ADR, K/R, etc.) of the last 10 games played
                        by the entered Faceit Player.
                    </td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/leaderboard_enter</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Inserts you into the Faceit Leaderboard of a server if one has been created.<br>
                        Note: This command requires you to track your Faceit account using "/track_player".</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/leaderboard_leave</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Removes you from the Faceit Leaderboard of a server the next time it is updated.</td>
                </div>
            </tr>
        </table>

        <h2 class="doc-category-title">Looking For Players Commands</h2>
        <table class="table-doc">
            <tr><th>Command</th><th>Parameters</th><th>Description</th></tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/lfp_create</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Sends you a DM that walks you through the provess of creating a LFP profile.<br>
                        Note: Creating a profile is required to match other players.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/lfp_update</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Lets you update/change any value in your LFP profile.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/lfp_delete</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Deletes your LFP profile and assoicated data in the database.<br>
                        Note: This needs to be done on each server where you created a profile.
                    </td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/lfp_extend</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Extends the duration of your LFP profile by 14 days.<br>
                        Note: After 14 days of inactivity (you not using any /lfp commands), your profile
                        will be automatically deleted.<br>
                        Note: A few days before your profile would get deleted, the Bot sends you a notifications
                        that deletion is imminent.
                    </td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/lfp</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Lets you look through other LFP profiles on this server.</td>
                </div>
            </tr>
        </table>

        <h2 class="doc-category-title">Voice Channel Commands</h2>
        <table class="table-doc">
            <tr><th>Command</th><th>Parameters</th><th>Description</th></tr>

            <tr>
                <div class="table-non-wrap">
                    <td>/voice_create</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Creates a temporary voice channel. After all users have left, the channel will be deleted.<br>
                    The host of a voice channel can change its privacy setting.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/voice_create_permanent</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Creates a permanent voice channel. After all users have left, the channel will be reset to its default state.<br>
                    Note: Only a server admin can use this command!</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/voice_close</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Makes the voice channel private. Other users need to use /voice_join to send a join request.<br>
                    Note: Permanent voice channels cannot be closed.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/voice_open</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Makes the voice channel public. Other users can join freely.<br>
                    Note: Permanent voice channels cannot be opened.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/voice_join</td>
                    <td>lobby_id</td>
                </div>
                <div class="table-wrap">
                    <td>Sends a join request to the voice channel of "lobby_id".<br>
                    Note: The lobby ID will be displayed in the channel upon running "/voice_close".</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/voice_hide</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Makes the voice channel hidden. Other users are not able to see it in the Server.<br>
                        Note: Permanent voice channels cannot be hidden.<br>
                        Note: This feature is a toggle, so to reveal a channel you need to run the command again.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/voice_toggle_elo</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Replaces the channel name with the average Faceit Elo or Premier Rating of all users in the channel.<br>
                    Note: This feature is a toggle that switches between Faceit Elo, Premier Rating and the default naming scheme.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/shuffle</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Splits all users in a channel into two evenly balanced teams in terms of their Faceit Elo.<br>
                        Note: This feature requires at least two users in a channel and will ignore all users who haven't set their Faceit elo yet.</td>
                </div>
            </tr>
        </table>

        <h2 class="doc-category-title">General User Commands</h2>
        <table class="table-doc">
            <tr><th>Command</th><th>Parameters</th><th>Description</th></tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/elo_set</td>
                    <td>faceit_elo<br>premier_rating</td>
                </div>
                <div class="table-wrap">
                    <td>Sets your Faceit Elo and/or your Premier Rating.<br>
                        Note: These values will be used when creating a LFP profile.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/elo_show</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Displays your current set Faceit Elo and Premier Rating.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/region</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Lets you choose your region, which will then be assigned to you as a server role.<br>
                        Note: This is required for creating a LFP profile and the Looking To Play Now feature.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/queue_mode</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Switches between your Faceit Elo or Premier Rating elo being displayed in the Looking To Play Now channel.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/delete_data</td>
                    <td>None</td>
                </div>
                <div class="table-wrap">
                    <td>Deletes any and all stored data of your Discord user-id in the database of the bot.<br>
                        Note: If you are on multiple servers using this bot, you only need to run the command
                        once to delete all data entries from all servers.</td>
                </div>
            </tr>
            <tr>
                <div class="table-non-wrap">
                    <td>/clutch</td>
                    <td>situation</td>
                </div>
                <div class="table-wrap">
                    <td>Simulates your performance in a 1vX situation.<br>
                        Note: You can improve the odds of a positive roll by setting your Faceit elo. The higher your elo, the higher the chances of a successful clutch!</td>
                </div>
            </tr>
        </table>


    </section>

    <!-- Quick Start Guide Section -->
    <section id="quickstart" class="section">
        <div class="quickstart">
            <div class="qs-header">
                <h2>Quick Start Guide</h2>
            </div>

            <ol class="qs-list">
                <li>
                    <h3>1. Invite the Bot</h3>
                    <p>Add the bot to your Discord server using the official invite link (Home section).</p>
                </li>

                <li>
                    <h3>2. Permissions</h3>
                    <p>Assign the Bot the required permissions by right clicking your server icon -> server settings -> roles and move the CS Bot all the way to the top.</p>
                </li>

                <li>
                    <h3>3. Setup your Server</h3>
                    <p>Use <code>/server_setup</code> to let the Bot create the basic channels required for some of its commands. 
                        You can move them around freely after, as long as they remain in the CS Bot category.</p>
                </li>

                <li>
                    <h3>4. Explore Commands</h3>
                    <p>Take a look at the Documentation section to get an idea of what the Bot is capable of.</p>
                </li>

                <li>
                    <h3>5. Bonus Tip</h3>
                    <p>Use <code>/leaderboard_create</code> to create a weekly (or more frequently) updated Leaderboard featuring all kinds of Faceit stats of participating 
                        server members over the last 7 days.</p>
                </li>
            </ol>
        </div>
    </section>

    <!-- ====================== TOS ====================== -->
    <section id="tos" class="section">
        <div class="tos">
            <h1>Terms of Service</h1>
            <p><strong>Last Updated:</strong> 19.11.2025</p>

            <p>
            These Terms of Service ("Terms") govern your access and use of the Cool CS Bot Discord bot. 
            By using the Bot, you agree to these Terms. If you do not agree, you must not use the Bot.
            </p>

            <h2>1. Eligibility</h2>
                <p>
                You must meet the minimum age requirements set by Discord’s Terms of Service. By using the Bot, 
                you confirm that you satisfy these requirements.
                </p>

            <h2>2. Description of the Service</h2>
                <p class="no-gap">The Bot offers optional features, including:</p>
                <ol>
                    <li>Leaderboards for Faceit related statistics</li>
                    <li>Faceit related statistics of past matches and your elo</li>
                    <li>Looking For Players (LFP) profiles and profile matching</li>
                    <li>Automated CS2 updates and Bot updates</li>
                    <li>Enhanced Voice Channel management</li>
                </ol>
                <p>All features are provided "as-is" and may be added, removed, or modified at any time.</p>

            <h2>3. User-Generated Content & User Responsibility</h2>
                <p class="no-gap">Users may submit information such as Faceit usernames, their region, spoken languages, 
                and other player information. Users are solely responsible for the content they submit and their interactions with others.</p>

                <p class="no-gap">The Bot operator is not liable for:</p>
                <ol>
                    <li>User behavior, harassment, spam, or abuse</li>
                    <li>Accuracy of user-submitted information</li>
                    <li>DMs exchanged between users</li>
                </ol>
                <p></p>

            <h2>4. Acceptable Use & Anti-Abuse Policy</h2>
                <p class="no-gap">Users agree not to:</p>
                <ol>
                    <li>Spam commands or automate usage of the Bot</li>
                    <li>Exploit, attack, overload, or reverse-engineer the Bot</li>
                    <li>Use the Bot for harassment, threats, stalking, or impersonation</li>
                    <li>Manipulate leaderboard data or misuse the LFP system</li>
                    <li>Bypass rate limits or command restrictions</li>
                </ol>
                <p>The operator may restrict or ban users violating these Terms.</p>

            <h2>5. Data Collection & GDPR Compliance</h2>
                <p class="no-gap">The Bot collects only data required to operate its features, including:</p>
                <ol>
                    <li>Discord User ID</li>
                    <li>Faceit username and public stats</li>
                    <li>LFP profile fields (region, country, spoken languages)</li>
                    <li>Timestamps for updates and participation</li>
                </ol>
                <p></p>

            <h3>Purpose of Storage</h3>
                <p class="no-gap">Data is used exclusively for Bot features such as, but not limited to, leaderboards,
                LFP searches, and abuse prevention.</p>

                <h3>User Rights</h3>
                <p class="no-gap">Users may request to view, modify, or delete their stored data at any time using provided commands.</p>

                <h3>Data Retention</h3>
                <p class="no-gap">
                LFP related DMs auto-delete after 24 hours.  
                Data is erased once a user opts out (by using the provided commands), a user leaves a server or a user does not
                actively use the Bot for 30 days. Created LFP profiles are deleted after 14 days of inactivity (not using any LFP features).
                </p>

            <h3>Data Protection</h3>
                <p>
                Reasonable security measures are applied, 
                but no system guarantees absolute security.  
                Users accept this risk.
                </p>

            <h2>6. No Warranty / Service Provided "As Is"</h2>
                <p>
                The Bot is provided without any warranties regarding uptime, accuracy, availability, reliability, 
                or error-free operation. Service interruptions may occur.
                </p>

            <h2>7. Limitation of Liability</h2>
                <p class="no-gap">To the fullest extent permitted by law, the Bot operator is not liable for:</p>
                <ol>
                    <li>User interactions or misconduct</li>
                    <li>Loss, corruption, or exposure of data</li>
                    <li>Service downtime, bugs, or errors</li>
                    <li>Unauthorized access, hacking, or malicious activity</li>
                    <li>Indirect, incidental, or consequential damages</li>
                </ol>
                <p>Users interact with the Bot at their own risk.</p>

            <h2>8. Server-Level Bans</h2>
            <p class="no-gap">
                Server owners and administrators have the authority to ban users from using the bot’s features within their server at any time and for any reason in accordance with their own community rules.
            </p>
            <p class="no-gap">
                Such bans remain active for a period of <strong>1 year</strong>, during which the affected user cannot request deletion of the minimal data required to maintain the ban. 
            </p>
            <p>
                For all matters related to how ban-related data is stored and retained please refer to the corresponding section in the Privacy Policy.
            </p>

            <h2>9. Right to Modify or Discontinue Service</h2>
                <p>
                The operator may update, change, suspend, or discontinue the Bot at any time without notice.
                Continuation of use after updates implies acceptance of revised Terms.
                </p>

            <h2>10. Termination</h2>
                <p>
                The operator may restrict or terminate access for any user who violates these Terms.  
                Users may delete their data or stop using the Bot at any time.
                </p>

            <h2>11. Governing Law</h2>
                <p>
                These Terms are governed by the laws applicable in the operator’s jurisdiction unless overridden by regional legal requirements.
                </p>

            <h2>12. Contact</h2>
                <p>
                For inquiries contact: sebcs.cs2@gmail.com
                </p>
        </div>
    </section>

    <!-- ====================== PRIVACY POLICY ====================== -->
    <section id="privacy" class="section">
        <div class="privacy-policy">
            <h1>Privacy Policy</h1>
            <p>
                This Privacy Policy explains what data the Bot collects, why it is collected, how long it is stored,
                and how users may request deletion. By using the Bot, you consent to the processing of the data
                described below for the purposes outlined.
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>1. Data Controller</h2>
            <p>
                The Data Controller for all processing carried out by the Bot is the Bot’s developer/owner.
                Contact information is provided at the bottom of the Terms Of Service.
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>2. Data Collected Automatically</h2>
            <h3>2.1 Guild Information</h3>
            <ul>
                <li>Guild ID</li>
                <li>User ID of the server owner</li>
            </ul>
            <p class="no-gap"><strong>Purpose:</strong> Required for bot functionality, command handling, and server-specific configuration.</p>
            <p><strong>Retention:</strong> Until the Bot is kicked, banned, or manually prompted to leave the server.</p>

            <h3>2.2 Dynamic Voice Channel System</h3>
            <h4>Temporary Channels</h4>
            <ul>
                <li>Guild ID</li>
                <li>Voice Channel ID</li>
                <li>Host User ID (first user joining an empty channel)</li>
            </ul>
            <p class="no-gap"><strong>Purpose:</strong> Managing dynamic voice channel ownership and lifecycle.</p>
            <p class="no-gap"><strong>Retention:</strong></p>
            <p style="padding-left: 25px;">
                • Host User ID is deleted as soon as the user leaves the channel.<br>
                • Channel data is deleted as soon as the channel becomes empty.
            </p>

            <h4>Permanent Channels</h4>
            <ul>
                <li>Guild ID</li>
                <li>Voice Channel ID</li>
                <li>Host User ID (first user joining an empty channel)</li>
            </ul>
            <p class="no-gap"><strong>Purpose:</strong> Provide persistent voice channels managed by the Bot.</p>
            <p class="no-gap"><strong>Retention:</strong></p>
            <p style="padding-left: 25px;"> 
                • Host User ID is deleted as soon as the user leaves the channel.<br>
                • Channel Data: Until a server admin or server owner deletes the channel.
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>3. Patchnote Notification System</h2>
            <ul>
                <li>Guild ID</li>
                <li>Channel ID</li>
            </ul>
            <p class="no-gap"><strong>Purpose:</strong> Sending CS2 update notifications and Bot update messages.</p>
            <p><strong>Retention:</strong> Until a server admin unsubscribes from notifications using the according command.</p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>4. Premium Server Data</h2>
            <ul>
                <li>Guild ID</li>
                <li>Premium tier information</li>
                <li>Date until Premium is valid</li>
            </ul>
            <p class="no-gap"><strong>Purpose:</strong> Determine premium feature access.</p>
            <p><strong>Retention:</strong> Until the premium period ends.</p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>5. User-Provided Data (Faceit & CS2 Statistics)</h2>
            <ul>
                <li>Faceit Elo</li>
                <li>Premier Rating</li>
                <li>Faceit Nickname</li>
                <li>Region</li>
            </ul>
            <p class="no-gap"><strong>Purpose:</strong> Enable leaderboard features and personalized statistics.</p>
            <p class="no-gap"><strong>Retention:</strong></p>
            <p style="padding-left: 25px;">
                • Until the user deletes their data via <code>/delete_data</code>, OR<br>
                • After 30 days of inactivity (no functionality of the Bot used).
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>6. Player Profile (LFP System)</h2>
            <p class="no-gap">For the Looking-For-Players system, the following data is stored:</p>
            <ul>
                <li>User ID</li>
                <li>Region</li>
                <li>Country</li>
                <li>Primary and Secondary Languages</li>
            </ul>
            <p><strong>Purpose:</strong> Allow players to create searchable profiles to find potential teammates.</p>

            <h3>6.1 Data Visibility</h3>
            <p>
                Search results anonymize usernames (e.g. "Player#VWXYZ").  
                When a like/connection is sent, the receiving user temporarily sees the sender’s full Discord username in order to allow them 
                to add the sender as a friend on Discord.
            </p>

            <h3>6.2 Data Retention</h3>
            <p class="no-gap" style="padding-left: 25px;">
                • Until the user deletes their profile via <code>/lfp_delete</code> or deletes all data via <code>/delete_data</code>, OR<br> 
                • After 14 days of inactivity.
            </p>
            <p>
                Users will be notified shortly before automatic deletion and may choose to extend storage for another 14 days.
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>7. Message Storage</h2>
            <p>
                Direct messages created by the Bot for LFP connection requests automatically delete themselves
                after 24 hours to maintain privacy and prevent unnecessary data retention.
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>8. Data Security</h2>
            <p>
                All data is stored on a restricted-access server.<br>
                Access is limited to the Bot’s developers.<br>
                No data is shared with third parties.
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>9. User Rights (GDPR)</h2>
            <p class="no-gap">Users have the following rights at any time:</p>
            <ul>
                <li>Right to access their stored data</li>
                <li>Right to request correction of inaccurate data</li>
                <li>Right to request deletion of their data via <code>/delete_data</code></li>
                <li>Right to withdraw consent by discontinuing use of the Bot</li>
            </ul>
            <p style="margin-bottom: 2px;"></p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>10. Retention of Minimal Data for Abuse Prevention</h2>
            <ul>
                <li>User ID</li>
            </ul>

            <p class="no-gap"><strong>Purpose:</strong> Abuse and misuse prevention.</p>
            <p><strong>Retention:</strong> 1 year starting from the day of the ban.</p>

            <p class="no-gap">
                In cases of misuse, spam, or malicious activity, the Bot may retain a minimal record consisting solely of the user’s Discord User ID
                for the purpose of enforcing bans or preventing repeated abuse.<br>
                This retention is based on the Bot Operator’s legitimate interest in maintaining the security and integrity of the service (GDPR Art. 6(1)(f), Recital 49).<br><br>
                This data:<br>
            </p>

            <ul>
                <li>is the minimum necessary to enforce a ban</li>
                <li>is not used for any other purpose</li>
                <li>is not displayed publicly</li>
                <li>is retained only as long as the ban is active</li>
            </ul>
            
            <p>
                Users may not request deletion of this specific data while a ban is active, as permitted under GDPR Art. 17(3)(e).
            </p>

            <!-- ---------------------------------------------------------------------- -->
            <h2>11. Changes to This Policy</h2>
            <p>
                This Privacy Policy may be updated to reflect improvements or changes in the Bot's functionality.<br>
                Continued use of the Bot implies acceptance of the latest version.
            </p>
        </div>

    </section>

    <!-- ====================== PREMIUM ====================== -->
    <section id="premium" class="section hidden">
        <div class="feature-box">
            <p>
                All essential features are available for free. Premium upgrades unlock additional functionality, extend data and performance limits, 
                and provide access to enhanced tools such as faster Faceit syncing, more profile slots, and advanced voice-channel features.
            </p>
        </div>

        <h1>Pricing</h1>
        <div class="free-tier-card">
            <h2>Free Tier</h2>
            <table class="table">
                <tbody class="always-visible">
                    <tr><th>Feature</th><th>Included</th></tr>
                    <tr><td>Patchnotes</td><td>✔</td></tr>
                    <tr><td>Leaderboard</td><td>Basic</td></tr>
                    <tr><td>Faceit Stats</td><td>Basic</td></tr>
                    <tr><td>Leaderboard Sync</td><td>Every 168h</td></tr>
                </tbody>
            </table>

            <details class="expandable">
                <summary>Show More</summary>

                <div class="collapsible-wrapper">
                    <table class="table">
                        <tbody class="collapsible-content">
                            <tr><td>LFP Profiles</td><td>5</td></tr>
                            <tr><td>Daily LFP Likes</td><td>1</td></tr>
                            <tr><td>Queue Slots</td><td>10</td></tr>
                            <tr><td>Shuffle Teams</td><td>No</td></tr>
                            <tr><td>VC Permanent</td><td>1</td></tr>
                            <tr><td>VC Temporary</td><td>3</td></tr>
                            <tr><td>VC Tools</td><td>Basic</td></tr>
                        </tbody>
                    </table>
                </div>
            </details>
        </div>

        <div class="premium-row">
            <div class="premium-card" data-href="https://www.patreon.com/c/CSSeb/membership">
                <h2>Plus</h2>
                <h3>2.50$ / Month</h3>
                <table class="table">
                        <tr><th>Feature</th><th>Included</th></tr>
                        <tr><td>Premium Servers</td><td>1</td></tr>
                        <tr><td>Leaderboard</td><td>Full</td></tr>
                        <tr><td>Leaderboard Sync</td><td>Every 168h</td></tr>
                        <tr><td>Faceit Stats</td><td>Full</td></tr>
                        <tr><td>LFP Profiles</td><td>15</td></tr>
                        <tr><td>Daily LFP Likes</td><td>2</td></tr>
                        <tr><td>Queue Slots</td><td>15</td></tr>
                        <tr><td>Shuffle Teams</td><td>✔</td></tr>
                        <tr><td>VC Permanent</td><td>3</td></tr>
                        <tr><td>VC Temporary</td><td>7</td></tr>
                        <tr><td>VC Tools</td><td>Full</td></tr>
                </table>
            </div>

            <div class="premium-card" data-href="https://www.patreon.com/c/CSSeb/membership">
                <h2>Premium</h2>
                <h3>6$ / Month</h3>
                <table class="table">
                        <tr><th>Feature</th><th>Included</th></tr>
                        <tr><td>Premium Servers</td><td>2</td></tr>
                        <tr><td>Leaderboard</td><td>Full</td></tr>
                        <tr><td>Leaderboard Sync</td><td>Every 72h</td></tr>
                        <tr><td>Faceit Stats</td><td>Full</td></tr>
                        <tr><td>LFP Profiles</td><td>30</td></tr>
                        <tr><td>Daily LFP Likes</td><td>3</td></tr>
                        <tr><td>Queue Slots</td><td>20</td></tr>
                        <tr><td>Shuffle Teams</td><td>✔</td></tr>
                        <tr><td>VC Permanent</td><td>5</td></tr>
                        <tr><td>VC Temporary</td><td>15</td></tr>
                        <tr><td>VC Tools</td><td>Full</td></tr>
                </table>
            </div>
            
            <div class="premium-card" data-href="https://www.patreon.com/c/CSSeb/membership">
                <h2>Ultra</h2>
                <h3>12.50$ / Month</h3>
                <table class="table">
                        <tr><th>Feature</th><th>Included</th></tr>
                        <tr><td>Premium Servers</td><td>3</td></tr>
                        <tr><td>Leaderboard</td><td>Full</td></tr>
                        <tr><td>Leaderboard Sync</td><td>Every 24h</td></tr>
                        <tr><td>Faceit Stats</td><td>Full</td></tr>
                        <tr><td>LFP Profiles</td><td>100</td></tr>
                        <tr><td>Daily LFP Likes</td><td>5</td></tr>
                        <tr><td>Queue Slots</td><td>30</td></tr>
                        <tr><td>Shuffle Teams</td><td>✔</td></tr>
                        <tr><td>VC Permanent</td><td>10</td></tr>
                        <tr><td>VC Temporary</td><td>30</td></tr>
                        <tr><td>VC Tools</td><td>Full</td></tr>
                </table>
            </div>
        </div>
    </section>

</main>

<footer class="footer">© Cool CS Bot Developer</footer>

<!-- ====================== JS: Page Switching + Fade Animation ====================== -->
<script>
    const links = document.querySelectorAll(".nav-link");
    const sections = document.querySelectorAll(".section");

    links.forEach(link => {
        link.addEventListener("click", () => {
            const target = link.getAttribute("data-target");

            links.forEach(l => l.classList.remove("active"));
            link.classList.add("active");

            sections.forEach(sec => {
                sec.classList.remove("active");
                if (sec.id === target) sec.classList.add("active");
            });
        });
    });
</script>

<script>
    (function () {

        const el = document.querySelector('.fade-in-on-scroll');
        if (!el) return;

        let lastScrollY = window.scrollY;
        let hasEnteredOnce = false; // prevents auto-fade-in on load

        function check() {
            const rect = el.getBoundingClientRect();
            const elTop = rect.top;
            const elHeight = rect.height;
            const thresholdIn = window.innerHeight * 0.8;   // fade IN when 20% enters
            const thresholdOut = window.innerHeight * 0.65;  // fade OUT when it goes above this

            const scrollingDown = window.scrollY > lastScrollY;
            const scrollingUp = !scrollingDown;

            // ---------------------
            // FADE IN: scroll down only
            // ---------------------
            if (scrollingDown && !hasEnteredOnce) {
                if (elTop < thresholdIn) {
                    el.classList.add('visible');
                    hasEnteredOnce = true;
                }
            }

            // ---------------------
            // FADE OUT: scroll up only
            // ---------------------
            if (scrollingUp && hasEnteredOnce) {
                if (elTop > thresholdOut) {
                    el.classList.remove('visible');
                    hasEnteredOnce = false;
                }
            }

            lastScrollY = window.scrollY;
        }

        window.addEventListener("scroll", check);
        window.addEventListener("resize", check);
        check();

    })();
</script>

<script>
    document.addEventListener("DOMContentLoaded", () => {
        document.querySelectorAll(".premium-card").forEach(table => {
            table.addEventListener("click", () => {
                const href = table.dataset.href;
                if (href) window.location.href = href;
            });
        });
    });
</script>

<script>
    document.addEventListener('DOMContentLoaded', () => {
        const imgs = document.querySelectorAll('.carousel-img');
        const lightbox = document.getElementById('lightbox');
        const lightboxImg = document.getElementById('lightbox-img');

        imgs.forEach(img => {
            img.addEventListener('click', () => {
                lightbox.style.display = 'flex';
                lightboxImg.src = img.src;
            });
        });

        lightbox.addEventListener('click', (e) => {
            if (e.target !== lightboxImg) {
                lightbox.style.display = 'none';
            }
        });

        // Carousel
        let index = 0;

        function updateCarousel() {
            imgs.forEach((img, i) => {
                img.classList.toggle('active', i === index);
            });
        }

        document.querySelector('.carousel-btn.left').onclick = () => {
            index = (index === 0) ? imgs.length - 1 : index - 1;
            updateCarousel();
        };

        document.querySelector('.carousel-btn.right').onclick = () => {
            index = (index + 1) % imgs.length;
            updateCarousel();
        };

        const showcase = document.querySelector('.carousel');

        const observer = new IntersectionObserver(
            (entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        showcase.classList.add('visible');   // fade in
                    } else {
                        showcase.classList.remove('visible'); // fade out
                    }
                });
            },
            { threshold: 0.2 } // trigger when 20% of the element is visible
        );

        observer.observe(showcase);
    });
</script>

<script>
    const videos = document.querySelectorAll(".interactive-video");

    // Updated observer with better sensitivity for tall videos
    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            const video = entry.target;

            if (entry.isIntersecting) {
                video.classList.add("in-view");
            } else {
                video.classList.remove("in-view");
                video.pause();
                video.classList.remove("playing");
            }
        });
    }, { 
        threshold: 0.1
    });

    // Observe all videos
    videos.forEach(video => observer.observe(video));

    // Pause all others (unchanged)
    function pauseOthers(except) {
        videos.forEach(v => {
            if (v !== except) {
                v.pause();
                v.classList.remove("playing");
            }
        });
    }

    // Interaction logic (unchanged)
    videos.forEach(video => {
        video.addEventListener("mouseenter", () => {
            pauseOthers(video);
            video.play();
            video.classList.add("playing");
        });

        video.addEventListener("click", () => {
            if (video.paused) {
                pauseOthers(video);
                video.play();
                video.classList.add("playing");
            } else {
                video.pause();
                video.classList.remove("playing");
            }
        });

        video.addEventListener("play", () => {
            video.classList.add("playing");
        });

        video.addEventListener("pause", () => {
            video.classList.remove("playing");
        });
    });
</script>




</body>
</html>
