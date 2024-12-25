css = '''
<style>
    /* Style global du chat */
    body {
        font-family: 'Roboto', sans-serif;
        background-color: #f4f4f9;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    /* Style des messages de chat */
    .chat-message {
        padding: 1rem;
        border-radius: 0.8rem;
        margin-bottom: 1rem;
        display: flex;
        box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1); /* Ombre pour profondeur */
        transition: all 0.3s ease-in-out; /* Animation fluide */
        background-color: #fff;
    }

    /* Message utilisateur */
    .chat-message.user {
        background-color: #4CAF50; /* Vert doux pour l'utilisateur */
        align-self: flex-end;
    }

    /* Message du bot */
    .chat-message.bot {
        background-color: #2196F3; /* Bleu pour le bot */
        align-self: flex-start;
    }

    /* Style de l'avatar */
    .chat-message .avatar {
        width: 18%;
    }

    .chat-message .avatar img {
        max-width: 60px;
        max-height: 60px;
        border-radius: 50%;
        object-fit: cover;
        border: 2px solid #fff; /* Bordure blanche pour mieux définir l'avatar */
    }

    /* Contenu des messages */
    .chat-message .message {
        width: 82%;
        padding: 0 1rem;
        color: #fff;
        font-size: 1rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    /* Nom de l'utilisateur ou du bot */
    .chat-message .name {
        font-weight: bold;
        font-size: 1.1rem;
        margin-bottom: 0.3rem;
    }

    /* Style pour les noms */
    .chat-message.user .name {
        color: #fff;
    }

    .chat-message.bot .name {
        color: #fff;
    }

    /* Effet hover sur les messages */
    .chat-message:hover {
        transform: translateY(-5px); /* Effet de levée au survol */
        box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.15); /* Ombre plus marquée */
    }
</style>
'''

bot_template = '''
<div class="chat-message bot">
    <div class="avatar">
        <img src="https://i.ibb.co/cN0nmSj/Screenshot-2023-05-28-at-02-37-21.png" alt="Bot Avatar" style="max-height: 60px; max-width: 60px; border-radius: 50%; object-fit: cover;">
    </div>
    <div class="message">
        <div class="name">Assistant Eva:</div>
        <div>{{MSG}}</div>
    </div>
</div>
'''

user_template = '''
<div class="chat-message user">
    <div class="avatar">
        <img src="https://i.ibb.co/rdZC7LZ/Photo-logo-1.png" alt="User Avatar">
    </div>    
    <div class="message">
        <div class="name">{{MSG}}</div>
    </div>
</div>
'''
