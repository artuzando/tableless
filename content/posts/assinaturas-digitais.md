---
title: Assinaturas Digitais e as Autoridades Certificadoras Aprovadas pela Adobe
authors: Artur Lemos
type: post
image: https://i.imgur.com/ExVMuL5.png
date: 2020-01-19
excerpt: Entenda o que são Autoridades Certificadoras e a forma mais segura de assinar um documento eletronicamente.
categories:
  - Tecnologia e Tendências
---

https://i.imgur.com/ExVMuL5.png

As ACs (Autoridades Certificadoras) ou CAs (Certificate Authorities) são entidades responsáveis pela emissão de certificados com Assinatura Digital reconhecidas no mundo todo. A relação completa dessa lista está disponível no link: https://helpx.adobe.com/br/acrobat/kb/approved-trust-list1.html

O processo para se tornar assinante de uma dessas autoridades é burocrático e tem um alto custo, por isso existem empresas afiliadas à elas que fornecem serviços de assinatura na nuvem para documentos PDF com custos menores, períodos de teste e até mesmo planos gratuitos com algumas limitações. Entre elas estão o Adobe Sign, da AC-Raiz Adobe, que orienta toda a cadeia de certificados acima das outras; e o Portal de Assinaturas, da AC-Raiz Brasileira ICP-Brasil, responsável pela infraestrutura de chaves públicas no Brasil.

Os recursos que podem ser vinculados às assinaturas digitais são:

Certificação Digital: O documento é selado e não permite nenhuma alteração. Mesmo para os que não forem certificados e permitirem novas assinaturas ou alterações posteriores, é sempre mantido o registro da versão anterior.

Carimbo do Tempo: O documento possui integridade, com data/hora segura padrão UTC. Caso o documento não o possua, o registro de tempo é baseado no relógio do servidor da empresa afiliada, tornando-o menos confiável.

Habilitação para LTV (Longa Validade): O documento é válido por um longo período de tempo ou para sempre. Mesmo para documentos com prazo expirado, a Assinatura Digital e o Carimbo do Tempo continuam valendo.

Chaves de Criptografia: O documento possui um par de chaves pública e privada para validar a autenticidade da Assinatura Digital. Isso é necessário para codificar uma mensagem de acesso compartilhado e decodificá-la através da confirmação do indivíduo para qual ela foi destinada.

Não Repúdio: O documento faz a interseção do Carimbo do Tempo e das Chaves de Criptografia para gerar um hash de origem que trará a garantia de que, posteriormente, o signatário não possa negar a sua própria assinatura.

Autenticação do Cliente e Proteção de E-mail: O documento é autenticado por confirmação de código via SMS, gerando um token virtual e particular vinculado ao endereço de IP, geolocalização e e-mail do usuário.

Os documentos assinados digitalmente são mais seguros quando possuem todas essas funções. Ao se inscrever para uma Assinatura Digital, reivindique da sua certificadora os componentes essenciais para garantir a sua proteção.
